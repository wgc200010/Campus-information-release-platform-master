<template>
  <div class="foot">
    <!-- Start of Footer -->
    <footer id="footer-wrapper">
      <div id="footer" class="container">
        <div class="row">
          <div class="span3">
            <section class="widget">
              <h3 class="title">网站主要功能</h3>
              <div class="textwidget">
                <p>
                  “buyi”是门头沟学院信息发布与交流平台，用户通过注册账号后就可以发布信息和评论，你可以在这里进行求助和帮助他人
                </p>
              </div>
            </section>
          </div>

          <div class="span3">
            <section class="widget">
              <h3 class="title">友情链接</h3>
              <ul>
                <li>
                  <a
                    href="http://www.pzhu.edu.cn/"
                    title="Lorem ipsum dolor sit amet,"
                    >门头沟学院官网</a
                  >
                </li>
                <li>
                  <a
                    href="http://jwci.pzhu.cn/jsxsd/"
                    title="Lorem ipsum dolor sit amet,"
                    >门头沟学院教务教务系统</a
                  >
                </li>
              </ul>
            </section>
          </div>

          <div class="span3">
            <section class="widget">
              <h3 class="title">公告</h3>
              <div id="twitter_update_list">
                  <p>
                    禁止在本平台上发表不当言论
                    禁止出现辱骂他人的语言，一经发现进行封号处理
                  </p>
              </div>
            </section>
          </div>

          <div class="span3">
            <section class="widget">
              <h3 class="title">客服中心</h3>
              <ul>
                <li>
                  <router-link to="/fankui" title="Lorem ipsum dolor sit amet,"
                    >意见反馈</router-link
                  >
                </li>
                <li>
                  <router-link to="/shensu" title="Lorem ipsum dolor sit amet,"
                    >账号申诉</router-link
                  >
                </li>
                <li>
                  <router-link to="/jubao" title="Lorem ipsum dolor sit amet,"
                    >不良行为举报</router-link
                  >
                </li>
              </ul>
            </section>
          </div>
        </div>
      </div>
      <!-- end of #footer -->

      <!-- Footer Bottom -->
      <div id="footer-bottom-wrapper">
        <div id="footer-bottom" class="container">
          <div class="row">
            <div class="span6">
              <p class="copyright">
                Copyright © 2019 - pzhu -
                <a
                  style="color: #858585;"
                  href="http://www.miit.gov.cn/"
                  target="“_blank”"
                  >陕 ICP 备 19016483 号-1</a
                >
                -
                <a
                  style="color: #858585;"
                  href="http://www.guoang.xyz/"
                  target="“_blank”"
                  >www.guoang.xyz</a
                >
              </p>
            </div>
          </div>
        </div>
      </div>
      <!-- End of Footer Bottom -->
    </footer>
    <!-- End of Footer -->
  </div>
</template>

<script>
export default {
  name: 'foot',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
