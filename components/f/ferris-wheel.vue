<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#iSNm8Ne)" class="d2kvgvbvc"><path fill="url(#inw7EIZ)" class="gzve40bpf"/><path fill="url(#iCLew0c)" class="gzve40bpf"/><path fill="url(#iiOzYfd)" class="gzve40bpf"/><path fill="url(#icfYjLD)" class="gzve40bpf"/><path fill="url(#iXTvtce)" class="gzve40bpf"/><path fill="url(#i1ll4Pe)" class="gzve40bpf"/><path fill="url(#ituj44b)" class="gzve40bpf"/><path fill="url(#imR5PwQ)" class="gzve40bpf"/><path fill="url(#iG6LfSc)" class="gzve40bpf"/><path fill="url(#i6Ihpgb)" class="gzve40bpf"/><path fill="url(#iw5XXwc)" class="gzve40bpf"/><path fill="url(#iJ1YAtk)" class="gzve40bpf"/></g><g filter="url(#ijwqw4d)"><path clip-rule="evenodd" class="zd-glpb3k"/></g><path fill="url(#iBjYhtd)" clip-rule="evenodd" class="p40kqibvx"/><path fill="url(#ix4AnWN)" clip-rule="evenodd" class="p40kqibvx"/><path fill="url(#ibPr3kd)" clip-rule="evenodd" class="p40kqibvx"/><path fill="url(#itssUts)" clip-rule="evenodd" class="p40kqibvx"/><path fill="url(#isO8nvb)" clip-rule="evenodd" class="p40kqibvx"/><path fill="url(#iIJVPgP)" clip-rule="evenodd" class="p40kqibvx"/><path fill="url(#iF116jb)" clip-rule="evenodd" class="p40kqibvx"/><path fill="url(#ijSoQze)" clip-rule="evenodd" class="p40kqibvx"/><path fill="url(#iDLed5y)" clip-rule="evenodd" class="p40kqibvx"/><path clip-rule="evenodd" class="rif8wbcho"/><path fill="url(#i0E3bCb)" clip-rule="evenodd" class="xc8zlzbhv"/><path fill="url(#itkNMOb)" clip-rule="evenodd" class="p4tqz185x"/><path fill="url(#iGviEDd)" clip-rule="evenodd" class="p4tqz185x"/><path fill="url(#iUqpyUd)" clip-rule="evenodd" class="p4tqz185x"/><path clip-rule="evenodd" class="xhzbhet8v"/><path fill="url(#iPC9NTx)" clip-rule="evenodd" class="tffd3c-pu"/><path clip-rule="evenodd" class="raalbcg5d"/><path fill="url(#icdOMNd)" clip-rule="evenodd" class="gkn4c8eyl"/><path fill="url(#ixicA5X)" clip-rule="evenodd" class="gkn4c8eyl"/><path clip-rule="evenodd" class="l7pow2bgu"/><path fill="url(#irfPBte)" clip-rule="evenodd" class="ybf2o-bfb"/><path fill="url(#iLw5Pod)" clip-rule="evenodd" class="ybf2o-bfb"/><path clip-rule="evenodd" class="r_6fpcc0q"/><path fill="url(#iUDN9Xb)" clip-rule="evenodd" class="yw4dz90vo"/><path clip-rule="evenodd" class="ybbew58sb"/><path fill="url(#ioTYDQb)" clip-rule="evenodd" class="d24i2abgf"/><path fill="url(#iH7Osnc)" clip-rule="evenodd" class="d24i2abgf"/><path clip-rule="evenodd" class="k8cteybfw"/><path fill="url(#iL4eFWc)" clip-rule="evenodd" class="sf677-bko"/><path fill="url(#iWVLpzd)" clip-rule="evenodd" class="sf677-bko"/><g filter="url(#iZhsqIb)"><rect fill="url(#ipY0Kbc)" class="h8tx__81k"/><rect fill="url(#iVnJTOc)" class="h8tx__81k"/></g><g filter="url(#iQNqUCe)"><path fill="url(#ipm19qd)" class="s050q1b5p"/><path fill="url(#i0YhTed)" class="s050q1b5p"/></g><g filter="url(#i3kE6Ke)"><rect fill="url(#itEeVvc)" class="qu9xdk-_h"/><rect fill="url(#iMpWD1d)" class="qu9xdk-_h"/></g><g filter="url(#i7dHRsc)"><path fill="url(#iKFkgQb)" class="gnw-dxinp"/><path fill="url(#i4bn64d)" class="gnw-dxinp"/></g><g filter="url(#iNi4r9d)"><rect fill="url(#imPAFjb)" class="f7rapz-rj"/><rect fill="url(#iyXlCwc)" class="f7rapz-rj"/></g><g filter="url(#ilgcI3b)"><path fill="url(#iYez8AF)" class="mw6-yhqft"/><path fill="url(#ijhjzLb)" class="mw6-yhqft"/></g><g filter="url(#ieuUwBu)"><rect fill="url(#iszA0mY)" class="mubc7q7ak"/><rect fill="url(#iXxrIbe)" class="mubc7q7ak"/></g><g filter="url(#idxUFCe)"><path fill="url(#i858Omu)" class="b_z7tqb-t"/><path fill="url(#i5WwBAI)" class="b_z7tqb-t"/></g><g filter="url(#ifhq94b)"><rect fill="url(#igGhp8d)" class="kadrjufve"/><rect fill="url(#ijHPdVc)" class="kadrjufve"/></g><g filter="url(#iYtDKHb)"><path fill="url(#iYrt5dd)" class="dh8k_bn2d"/><path fill="url(#iGL40Pe)" class="dh8k_bn2d"/></g><g filter="url(#ib8ZrYd)"><rect fill="url(#iC4A6Kd)" class="v4am1yb9a"/><rect fill="url(#iIKnBtZ)" class="v4am1yb9a"/></g><g filter="url(#ikbBGBc)"><path fill="url(#iaabLEd)" class="yvub0oggx"/><path fill="url(#iifXC6d)" class="yvub0oggx"/></g><g filter="url(#iBcokHc)"><rect fill="url(#ixGMhsU)" class="m_9v0kbjs"/><rect fill="url(#iH9lTje)" class="m_9v0kbjs"/></g><g filter="url(#i2BwPtc)"><path fill="url(#iBKkIcU)" class="dw2b7qcgg"/><path fill="url(#iTwed8b)" class="dw2b7qcgg"/></g><g filter="url(#i7gq1vd)"><rect fill="url(#iY2exMe)" class="akdgykb2y"/><rect fill="url(#ixJwqmc)" class="akdgykb2y"/></g><g filter="url(#ixxPBuT)"><path fill="url(#iDxV1Le)" class="xmgsf_b7p"/><path fill="url(#ipFIHvb)" class="xmgsf_b7p"/></g><g filter="url(#iPplCSd)"><circle class="znxfl-8gg"/></g><circle fill="url(#iZv0Ijd)" class="p8j_j_bxx"/><g filter="url(#iEsgLwi)"><path clip-rule="evenodd" class="xsgosw_vs"/></g><path fill="url(#idslKhd)" clip-rule="evenodd" class="p481wjbcn"/><path fill="url(#iKTzMqd)" clip-rule="evenodd" class="p481wjbcn"/><path fill="url(#iKA1r5c)" clip-rule="evenodd" class="p481wjbcn"/><g filter="url(#iubXHyd)"><circle stroke="url(#iLg4jdb)" class="tderzlbxz"/></g><g filter="url(#i5RbfTb)"><path stroke="url(#ikxg7Ee)" class="xtro7g7do"/></g><defs><radialGradient id="iCLew0c" cx="0" cy="0" r="1" gradientTransform="matrix(1 -.5 2.45 4.9 19.515 23.045)" gradientUnits="userSpaceOnUse"><stop class="iapld1boa"/><stop offset="1" class="oh7b9b82a"/></radialGradient><radialGradient id="iiOzYfd" cx="0" cy="0" r="1" gradientTransform="matrix(1.64064 4.07813 -1.06221 .42733 16.953 16.123)" gradientUnits="userSpaceOnUse"><stop class="uw1rxccqd"/><stop offset="1" class="bf_8-obpr"/></radialGradient><radialGradient id="icfYjLD" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 -.25 1.66753 3.75194 17.062 18.217)" gradientUnits="userSpaceOnUse"><stop offset=".345" class="yhfl73dmd"/><stop offset="1" class="n6arjdb9t"/></radialGradient><radialGradient id="iXTvtce" cx="0" cy="0" r="1" gradientTransform="matrix(1 .65625 -.35196 .53633 21.547 28.357)" gradientUnits="userSpaceOnUse"><stop offset=".294" class="r8emc48kl"/><stop offset="1" class="l9pvwvb1t"/></radialGradient><radialGradient id="i1ll4Pe" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 .35937 -1.13271 -2.31471 22.843 27.482)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="xelsirb9t"/><stop offset="1" class="y96sd_b-d"/></radialGradient><radialGradient id="ituj44b" cx="0" cy="0" r="1" gradientTransform="matrix(-.73243 .19764 -.14571 -.53999 27.015 29.166)" gradientUnits="userSpaceOnUse"><stop class="t_khuvvui"/><stop offset="1" class="zjcakryiv"/></radialGradient><radialGradient id="iG6LfSc" cx="0" cy="0" r="1" gradientTransform="matrix(.9882 0 0 .43016 8.798 28.655)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="ctnrgnbyt"/><stop offset="1" class="co89d-sus"/></radialGradient><radialGradient id="i6Ihpgb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.27884 -.60453 2.34283 -4.95608 12.285 23.935)" gradientUnits="userSpaceOnUse"><stop class="khdui9bgk"/><stop offset="1" class="zl8h5lbwr"/></radialGradient><radialGradient id="iw5XXwc" cx="0" cy="0" r="1" gradientTransform="rotate(112.674 2.27 13.232)scale(5.66982 1.30196)" gradientUnits="userSpaceOnUse"><stop class="zmz05ebqc"/><stop offset="1" class="j7fzu-k1p"/></radialGradient><radialGradient id="iBjYhtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20988 -.65596 .27437 -.50606 21.398 6.108)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="zzgtq8yut"/><stop offset="1" class="x6o2sabtt"/></radialGradient><radialGradient id="ix4AnWN" cx="0" cy="0" r="1" gradientTransform="rotate(-116.906 8.04 -.817)scale(1.17396 5.34845)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="ync_4qb8l"/><stop offset="1" class="y4_ddpblg"/></radialGradient><radialGradient id="ibPr3kd" cx="0" cy="0" r="1" gradientTransform="rotate(143.881 6.636 4.643)scale(2.86275 1.36997)" gradientUnits="userSpaceOnUse"><stop offset=".072" class="ujy6bwoxf"/><stop offset="1" class="td43repzy"/></radialGradient><radialGradient id="itssUts" cx="0" cy="0" r="1" gradientTransform="rotate(137.684 2.73 5.969)scale(2.83153 1.99274)" gradientUnits="userSpaceOnUse"><stop offset=".199" class="s2-mefblg"/><stop offset="1" class="v52v6f_zk"/></radialGradient><radialGradient id="isO8nvb" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 1.17187 -2.555 1.4308 5.969 15.498)" gradientUnits="userSpaceOnUse"><stop class="lld4y1kbv"/><stop offset="1" class="rjdskei1k"/></radialGradient><radialGradient id="iIJVPgP" cx="0" cy="0" r="1" gradientTransform="matrix(-.625 -1.6875 .91833 -.34012 7.39 19.67)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="n5i2-0bvm"/><stop offset="1" class="rugn9wbne"/></radialGradient><radialGradient id="iF116jb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26563 -.26563 .20963 -.99882 14.453 23.139)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="a59qtrbjt"/><stop offset="1" class="td0j44bbs"/></radialGradient><radialGradient id="ijSoQze" cx="0" cy="0" r="1" gradientTransform="matrix(-2.21874 .9375 -.50182 -1.18763 21.328 21.576)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="okf7hbbwh"/><stop offset="1" class="y-72o53eb"/></radialGradient><radialGradient id="iDLed5y" cx="0" cy="0" r="1" gradientTransform="rotate(136.134 9.398 13.008)scale(2.23224 1.03573)" gradientUnits="userSpaceOnUse"><stop class="gawaos8ql"/><stop offset="1" class="gn2erv6cb"/></radialGradient><radialGradient id="itkNMOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.47675 .52867 0 16.078 20.454)" gradientUnits="userSpaceOnUse"><stop class="m5aleub_i"/><stop offset="1" class="n_0497j3z"/></radialGradient><radialGradient id="iGviEDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92188 -1.29688 0 16.078 20.764)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="haeod2bol"/><stop offset="1" class="k2b1u6b7j"/></radialGradient><radialGradient id="ixicA5X" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03125 .78126 -.79287 -1.04658 21.672 8.764)" gradientUnits="userSpaceOnUse"><stop class="lu-cqab0p"/><stop offset="1" class="talb2713b"/></radialGradient><radialGradient id="iWVLpzd" cx="0" cy="0" r="1" gradientTransform="rotate(102.317 6.596 16.342)scale(1.17194 1.33587)" gradientUnits="userSpaceOnUse"><stop class="lu-cqab0p"/><stop offset="1" class="talb2713b"/></radialGradient><radialGradient id="iVnJTOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.77695 3.28047 0 16.082 4.041)" gradientUnits="userSpaceOnUse"><stop class="ms9fzabbu"/><stop offset="1" class="wn_bnqbvx"/></radialGradient><radialGradient id="i0YhTed" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.91406 -.82813 0 17.203 3.693)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="bq9apmbsk"/><stop offset="1" class="uwf77hb5j"/></radialGradient><radialGradient id="iMpWD1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.77695 3.28047 0 9.05 6.951)" gradientUnits="userSpaceOnUse"><stop class="ms9fzabbu"/><stop offset="1" class="wn_bnqbvx"/></radialGradient><radialGradient id="i4bn64d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.91406 -.82813 0 10.172 6.604)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="bq9apmbsk"/><stop offset="1" class="uwf77hb5j"/></radialGradient><radialGradient id="iyXlCwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.77695 3.28047 0 6.129 13.994)" gradientUnits="userSpaceOnUse"><stop class="ms9fzabbu"/><stop offset="1" class="wn_bnqbvx"/></radialGradient><radialGradient id="ijhjzLb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.91406 -.82813 0 7.25 13.646)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="bq9apmbsk"/><stop offset="1" class="uwf77hb5j"/></radialGradient><radialGradient id="iXxrIbe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.77695 3.28047 0 9.05 21.037)" gradientUnits="userSpaceOnUse"><stop class="ms9fzabbu"/><stop offset="1" class="wn_bnqbvx"/></radialGradient><radialGradient id="i5WwBAI" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.91406 -.82813 0 10.172 20.69)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="bq9apmbsk"/><stop offset="1" class="uwf77hb5j"/></radialGradient><radialGradient id="ijHPdVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.77695 3.28047 0 16.078 23.931)" gradientUnits="userSpaceOnUse"><stop class="ms9fzabbu"/><stop offset="1" class="wn_bnqbvx"/></radialGradient><radialGradient id="iGL40Pe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.91406 -.82813 0 17.199 23.584)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="bq9apmbsk"/><stop offset="1" class="uwf77hb5j"/></radialGradient><radialGradient id="iIKnBtZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.77695 3.28047 0 23.105 21.037)" gradientUnits="userSpaceOnUse"><stop class="ms9fzabbu"/><stop offset="1" class="wn_bnqbvx"/></radialGradient><radialGradient id="iifXC6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.91406 -.82813 0 24.227 20.69)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="bq9apmbsk"/><stop offset="1" class="uwf77hb5j"/></radialGradient><radialGradient id="iH9lTje" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.77695 3.28047 0 26.012 13.994)" gradientUnits="userSpaceOnUse"><stop class="ms9fzabbu"/><stop offset="1" class="wn_bnqbvx"/></radialGradient><radialGradient id="iTwed8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.91406 -.82813 0 27.133 13.646)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="bq9apmbsk"/><stop offset="1" class="uwf77hb5j"/></radialGradient><radialGradient id="ixJwqmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.77695 3.28047 0 23.113 6.955)" gradientUnits="userSpaceOnUse"><stop class="ms9fzabbu"/><stop offset="1" class="wn_bnqbvx"/></radialGradient><radialGradient id="ipFIHvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.91406 -.82813 0 24.234 6.607)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="bq9apmbsk"/><stop offset="1" class="uwf77hb5j"/></radialGradient><radialGradient id="iZv0Ijd" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 -2.46875 2.9497 3.88315 14.797 15.326)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="rwr8rn_nb"/><stop offset="1" class="zuz4jibbq"/></radialGradient><radialGradient id="idslKhd" cx="0" cy="0" r="1" gradientTransform="rotate(133.603 8.543 8.83)scale(.90625 1.27102)" gradientUnits="userSpaceOnUse"><stop class="emxs8p71x"/><stop offset="1" class="n4e8pac0v"/></radialGradient><radialGradient id="iKTzMqd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -1.79696 23.61 13.986)" gradientUnits="userSpaceOnUse"><stop class="emxs8p71x"/><stop offset="1" class="n4e8pac0v"/></radialGradient><radialGradient id="iKA1r5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 .4375 -1.38661 -2.32754 22.594 11.216)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="jsfc9h2ld"/><stop offset="1" class="qvs1eybyc"/></radialGradient><linearGradient id="inw7EIZ" x1="16.078" x2="24.14" y1="29.42" y2="29.42" gradientUnits="userSpaceOnUse"><stop class="m-8nolb2a"/><stop offset="1" class="x2ge7y1za"/></linearGradient><linearGradient id="imR5PwQ" x1="5.078" x2="5.722" y1="29.947" y2="29.947" gradientUnits="userSpaceOnUse"><stop offset=".27" class="enc1g-2ki"/><stop offset="1" class="ogaivek7d"/></linearGradient><linearGradient id="iJ1YAtk" x1="16.078" x2="16.078" y1="29.947" y2="29.498" gradientUnits="userSpaceOnUse"><stop class="qclsl1bte"/><stop offset="1" class="hz7fd4b7n"/></linearGradient><linearGradient id="i0E3bCb" x1="15.638" x2="16.283" y1="9.693" y2="9.693" gradientUnits="userSpaceOnUse"><stop class="cbkc83bbd"/><stop offset="1" class="ny6n6k9ns"/></linearGradient><linearGradient id="iUqpyUd" x1="16.648" x2="16.285" y1="19.583" y2="19.583" gradientUnits="userSpaceOnUse"><stop class="mi4zwzfmr"/><stop offset="1" class="o3446bisv"/></linearGradient><linearGradient id="iPC9NTx" x1="12.437" x2="12.893" y1="10.967" y2="10.511" gradientUnits="userSpaceOnUse"><stop class="cbkc83bbd"/><stop offset="1" class="ny6n6k9ns"/></linearGradient><linearGradient id="icdOMNd" x1="18.914" x2="19.267" y1="10.302" y2="10.656" gradientUnits="userSpaceOnUse"><stop offset=".155" class="ldpfvmrly"/><stop offset="1" class="j078q_pzn"/></linearGradient><linearGradient id="irfPBte" x1="12.605" x2="12.148" y1="17.947" y2="17.49" gradientUnits="userSpaceOnUse"><stop class="cbkc83bbd"/><stop offset="1" class="ny6n6k9ns"/></linearGradient><linearGradient id="iLw5Pod" x1="14.508" x2="13.533" y1="15.131" y2="16.105" gradientUnits="userSpaceOnUse"><stop class="cbkc83bbd"/><stop offset="1" class="ny6n6k9ns"/></linearGradient><linearGradient id="iUDN9Xb" x1="20.015" x2="19.567" y1="17.311" y2="17.767" gradientUnits="userSpaceOnUse"><stop class="olhq6ogmc"/><stop offset="1" class="c-m5jgbme"/></linearGradient><linearGradient id="ioTYDQb" x1="11.123" x2="11.123" y1="14.324" y2="13.679" gradientUnits="userSpaceOnUse"><stop class="cbkc83bbd"/><stop offset="1" class="ny6n6k9ns"/></linearGradient><linearGradient id="iH7Osnc" x1="14.248" x2="12.957" y1="13.679" y2="13.679" gradientUnits="userSpaceOnUse"><stop class="cbkc83bbd"/><stop offset="1" class="ny6n6k9ns"/></linearGradient><linearGradient id="iL4eFWc" x1="20.892" x2="20.892" y1="13.384" y2="14.231" gradientUnits="userSpaceOnUse"><stop class="ldpfvmrly"/><stop offset="1" class="j078q_pzn"/></linearGradient><linearGradient id="ipY0Kbc" x1="15.037" x2="17.078" y1="3.55" y2="3.55" gradientUnits="userSpaceOnUse"><stop class="jvkwuupqq"/><stop offset="1" class="u_lr15bqk"/></linearGradient><linearGradient id="ipm19qd" x1="14.765" x2="17.765" y1="4.701" y2="4.701" gradientUnits="userSpaceOnUse"><stop class="r77zsikrk"/><stop offset="1" class="yvwckabsx"/></linearGradient><linearGradient id="itEeVvc" x1="8.006" x2="10.047" y1="6.461" y2="6.461" gradientUnits="userSpaceOnUse"><stop class="jvkwuupqq"/><stop offset="1" class="u_lr15bqk"/></linearGradient><linearGradient id="iKFkgQb" x1="7.734" x2="10.734" y1="7.611" y2="7.611" gradientUnits="userSpaceOnUse"><stop class="r77zsikrk"/><stop offset="1" class="yvwckabsx"/></linearGradient><linearGradient id="imPAFjb" x1="5.084" x2="8.117" y1="13.504" y2="13.504" gradientUnits="userSpaceOnUse"><stop class="jvkwuupqq"/><stop offset="1" class="u_lr15bqk"/></linearGradient><linearGradient id="iYez8AF" x1="4.812" x2="7.812" y1="14.654" y2="14.654" gradientUnits="userSpaceOnUse"><stop class="r77zsikrk"/><stop offset="1" class="yvwckabsx"/></linearGradient><linearGradient id="iszA0mY" x1="8.006" x2="11.039" y1="20.546" y2="20.546" gradientUnits="userSpaceOnUse"><stop class="jvkwuupqq"/><stop offset="1" class="u_lr15bqk"/></linearGradient><linearGradient id="i858Omu" x1="7.734" x2="10.734" y1="21.697" y2="21.697" gradientUnits="userSpaceOnUse"><stop class="r77zsikrk"/><stop offset="1" class="yvwckabsx"/></linearGradient><linearGradient id="igGhp8d" x1="15.033" x2="18.066" y1="23.441" y2="23.441" gradientUnits="userSpaceOnUse"><stop class="jvkwuupqq"/><stop offset="1" class="u_lr15bqk"/></linearGradient><linearGradient id="iYrt5dd" x1="14.761" x2="17.762" y1="24.591" y2="24.591" gradientUnits="userSpaceOnUse"><stop class="r77zsikrk"/><stop offset="1" class="yvwckabsx"/></linearGradient><linearGradient id="iC4A6Kd" x1="22.061" x2="25.094" y1="20.546" y2="20.546" gradientUnits="userSpaceOnUse"><stop class="jvkwuupqq"/><stop offset="1" class="u_lr15bqk"/></linearGradient><linearGradient id="iaabLEd" x1="21.789" x2="24.789" y1="21.697" y2="21.697" gradientUnits="userSpaceOnUse"><stop class="r77zsikrk"/><stop offset="1" class="yvwckabsx"/></linearGradient><linearGradient id="ixGMhsU" x1="24.967" x2="28" y1="13.504" y2="13.504" gradientUnits="userSpaceOnUse"><stop class="jvkwuupqq"/><stop offset="1" class="u_lr15bqk"/></linearGradient><linearGradient id="iBKkIcU" x1="24.695" x2="27.695" y1="14.654" y2="14.654" gradientUnits="userSpaceOnUse"><stop class="r77zsikrk"/><stop offset="1" class="yvwckabsx"/></linearGradient><linearGradient id="iY2exMe" x1="22.069" x2="25.102" y1="6.464" y2="6.464" gradientUnits="userSpaceOnUse"><stop class="jvkwuupqq"/><stop offset="1" class="u_lr15bqk"/></linearGradient><linearGradient id="iDxV1Le" x1="21.797" x2="24.797" y1="7.615" y2="7.615" gradientUnits="userSpaceOnUse"><stop class="r77zsikrk"/><stop offset="1" class="yvwckabsx"/></linearGradient><linearGradient id="iLg4jdb" x1="10.797" x2="22.078" y1="13.986" y2="13.986" gradientUnits="userSpaceOnUse"><stop class="r0jo6i0wx"/><stop offset="1" class="n7i_e3b2c"/></linearGradient><linearGradient id="ikxg7Ee" x1="6.519" x2="26.05" y1="30.352" y2="30.352" gradientUnits="userSpaceOnUse"><stop class="eg8n1gx4k"/><stop offset="1" class="q57gsfbfa"/></linearGradient><filter id="iSNm8Ne" width="22.15" height="15.326" x="5.078" y="14.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.376471 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/></filter><filter id="ijwqw4d" width="20.3" height="20.3" x="5.928" y="3.836" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.466667 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.941176 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8600" result="effect2_innerShadow_18_8600"/></filter><filter id="iZhsqIb" width="4.977" height="4.077" x="13.594" y="2.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.878431 0 0 0 0 0.921569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8600" result="effect2_innerShadow_18_8600"/></filter><filter id="iQNqUCe" width="4.877" height="2.586" x="13.694" y="3.443" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.521569 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.254902 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8600" result="effect2_innerShadow_18_8600"/></filter><filter id="i3kE6Ke" width="4.977" height="4.077" x="6.562" y="4.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.878431 0 0 0 0 0.921569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8600" result="effect2_innerShadow_18_8600"/></filter><filter id="i7dHRsc" width="4.877" height="2.586" x="6.662" y="6.354" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.521569 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.254902 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8600" result="effect2_innerShadow_18_8600"/></filter><filter id="iNi4r9d" width="4.977" height="4.077" x="3.64" y="12.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.878431 0 0 0 0 0.921569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8600" result="effect2_innerShadow_18_8600"/></filter><filter id="ilgcI3b" width="4.877" height="2.586" x="3.74" y="13.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.521569 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.254902 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8600" result="effect2_innerShadow_18_8600"/></filter><filter id="ieuUwBu" width="4.977" height="4.077" x="6.562" y="19.049" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.878431 0 0 0 0 0.921569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8600" result="effect2_innerShadow_18_8600"/></filter><filter id="idxUFCe" width="4.877" height="2.586" x="6.662" y="20.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.521569 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.254902 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8600" result="effect2_innerShadow_18_8600"/></filter><filter id="ifhq94b" width="4.977" height="4.077" x="13.59" y="21.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.878431 0 0 0 0 0.921569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8600" result="effect2_innerShadow_18_8600"/></filter><filter id="iYtDKHb" width="4.877" height="2.586" x="13.69" y="23.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.521569 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.254902 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8600" result="effect2_innerShadow_18_8600"/></filter><filter id="ib8ZrYd" width="4.977" height="4.077" x="20.617" y="19.049" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8600" result="effect2_innerShadow_18_8600"/></filter><filter id="ikbBGBc" width="4.877" height="2.586" x="20.717" y="20.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.521569 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.254902 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8600" result="effect2_innerShadow_18_8600"/></filter><filter id="iBcokHc" width="4.977" height="4.077" x="23.523" y="12.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8600" result="effect2_innerShadow_18_8600"/></filter><filter id="i2BwPtc" width="4.877" height="2.586" x="23.623" y="13.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.521569 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.254902 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8600" result="effect2_innerShadow_18_8600"/></filter><filter id="i7gq1vd" width="4.977" height="4.077" x="20.625" y="4.967" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8600" result="effect2_innerShadow_18_8600"/></filter><filter id="ixxPBuT" width="4.877" height="2.586" x="20.725" y="6.357" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.521569 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.254902 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8600" result="effect2_innerShadow_18_8600"/></filter><filter id="iPplCSd" width="5.361" height="5.611" x="13.597" y="11.106" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.498039 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.529412 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8600" result="effect2_innerShadow_18_8600"/></filter><filter id="iEsgLwi" width="14.214" height="14.214" x="8.971" y="6.879" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.490196 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8600"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.537255 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8600" result="effect2_innerShadow_18_8600"/></filter><filter id="iubXHyd" width="13.664" height="13.664" x="9.308" y="7.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_8600" stdDeviation=".125"/></filter><filter id="i5RbfTb" width="21.168" height=".8" x="5.514" y="28.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_8600" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ferris-wheel" /></template>
<style>
.a59qtrbjt {
  stop-color: var(--svg-color--b47c2d, #B47C2D);
}

.akdgykb2y {
  width: 3.977px;
  height: 3.977px;
  x: 21.125px;
  y: 4.967px;
  rx: 0.7px;
}

.b_z7tqb-t {
  d: path("M10.789 20.69a.25.25 0 0 1 .25.25v1.385a.7.7 0 0 1-.7.7H7.762a.7.7 0 0 1-.7-.7v-1.386a.25.25 0 0 1 .25-.25z");
}

.bf_8-obpr {
  stop-color: var(--svg-color--816497, #816497);
  stop-opacity: 0;
}

.bq9apmbsk {
  stop-color: var(--svg-color--736aa5, #736AA5);
}

.c-m5jgbme {
  stop-color: var(--svg-color--695677, #695677);
  stop-opacity: 0;
}

.cbkc83bbd {
  stop-color: var(--svg-color--44324e, #44324E);
}

.co89d-sus {
  stop-color: var(--svg-color--7b777d, #7B777D);
  stop-opacity: 0;
}

.ctnrgnbyt {
  stop-color: var(--svg-color--7b777d, #7B777D);
}

.d24i2abgf {
  fill-rule: evenodd;
  d: path("M6.105 13.384H16.14v1H6.105z");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dh8k_bn2d {
  d: path("M17.816 23.584a.25.25 0 0 1 .25.25v1.386a.7.7 0 0 1-.7.7H14.79a.7.7 0 0 1-.7-.7v-1.386a.25.25 0 0 1 .25-.25z");
}

.dw2b7qcgg {
  d: path("M27.75 13.647a.25.25 0 0 1 .25.25v1.385a.7.7 0 0 1-.7.7h-2.577a.7.7 0 0 1-.7-.7v-1.386a.25.25 0 0 1 .25-.25z");
}

.eg8n1gx4k {
  stop-color: var(--svg-color--b19bc8, #B19BC8);
}

.emxs8p71x {
  stop-color: var(--svg-color--a87b2b, #A87B2B);
}

.enc1g-2ki {
  stop-color: var(--svg-color--7f7588, #7F7588);
}

.f7rapz-rj {
  width: 3.977px;
  height: 3.977px;
  x: 4.14px;
  y: 12.006px;
  rx: 0.7px;
}

.ft5dv1b6b {
  fill: none;
}

.gawaos8ql {
  stop-color: var(--svg-color--c1783c, #C1783C);
}

.gkn4c8eyl {
  fill-rule: evenodd;
  d: path("m22.04 7.176l-6.253 6.253l.707.707l6.253-6.253z");
}

.gn2erv6cb {
  stop-color: var(--svg-color--c1783c, #C1783C);
  stop-opacity: 0;
}

.gnw-dxinp {
  d: path("M10.789 6.604a.25.25 0 0 1 .25.25v1.385a.7.7 0 0 1-.7.7H7.762a.7.7 0 0 1-.7-.7V6.854a.25.25 0 0 1 .25-.25z");
}

.gzve40bpf {
  d: path("M8.371 28.947a.75.75 0 0 0 .68-.433l6.463-13.893l.58.27l.573-.266l6.461 13.889a.75.75 0 0 0 .68.433h2.77a.5.5 0 1 1 0 1h-21a.5.5 0 0 1 0-1zm1.736-.569a.4.4 0 0 0 .362.57h11.24a.4.4 0 0 0 .364-.57L16.09 15.517z");
}

.h8tx__81k {
  width: 3.977px;
  height: 3.977px;
  x: 14.094px;
  y: 2.053px;
  rx: 0.7px;
}

.haeod2bol {
  stop-color: var(--svg-color--4d2c5d, #4D2C5D);
}

.hz7fd4b7n {
  stop-color: var(--svg-color--a764dc, #A764DC);
  stop-opacity: 0;
}

.iapld1boa {
  stop-color: var(--svg-color--9771b1, #9771B1);
}

.j078q_pzn {
  stop-color: var(--svg-color--513f59, #513F59);
  stop-opacity: 0;
}

.j7fzu-k1p {
  stop-color: var(--svg-color--704d82, #704D82);
  stop-opacity: 0;
}

.jsfc9h2ld {
  stop-color: var(--svg-color--ffe653, #FFE653);
}

.jvkwuupqq {
  stop-color: var(--svg-color--a69eb0, #A69EB0);
}

.k2b1u6b7j {
  stop-color: var(--svg-color--4d2c5d, #4D2C5D);
  stop-opacity: 0;
}

.k8cteybfw {
  fill: var(--svg-color--8b50d3, #8B50D3);
  fill-rule: evenodd;
  d: path("M25.91 13.384H15.874v1H25.91z");
}

.kadrjufve {
  width: 3.977px;
  height: 3.977px;
  x: 14.09px;
  y: 21.943px;
  rx: 0.7px;
}

.khdui9bgk {
  stop-color: var(--svg-color--9673ac, #9673AC);
}

.l7pow2bgu {
  fill: var(--svg-color--7a4fac, #7A4FAC);
  fill-rule: evenodd;
  d: path("m8.152 21.07l7.576-7.576l.707.707l-7.576 7.576z");
}

.l9pvwvb1t {
  stop-color: var(--svg-color--8b838e, #8B838E);
  stop-opacity: 0;
}

.ldpfvmrly {
  stop-color: var(--svg-color--513f59, #513F59);
}

.lld4y1kbv {
  stop-color: var(--svg-color--bd6f43, #BD6F43);
}

.lu-cqab0p {
  stop-color: var(--svg-color--4c3658, #4C3658);
}

.m_9v0kbjs {
  width: 3.977px;
  height: 3.977px;
  x: 24.023px;
  y: 12.006px;
  rx: 0.7px;
}

.m-8nolb2a {
  stop-color: var(--svg-color--998ea5, #998EA5);
}

.m5aleub_i {
  stop-color: var(--svg-color--8b60c0, #8B60C0);
}

.mi4zwzfmr {
  stop-color: var(--svg-color--614679, #614679);
}

.ms9fzabbu {
  stop-color: var(--svg-color--9893a0, #9893A0);
}

.mubc7q7ak {
  width: 3.977px;
  height: 3.977px;
  x: 7.062px;
  y: 19.049px;
  rx: 0.7px;
}

.mw6-yhqft {
  d: path("M7.867 13.647a.25.25 0 0 1 .25.25v1.385a.7.7 0 0 1-.7.7H4.84a.7.7 0 0 1-.7-.7v-1.386a.25.25 0 0 1 .25-.25z");
}

.n_0497j3z {
  stop-color: var(--svg-color--653e93, #653E93);
}

.n4e8pac0v {
  stop-color: var(--svg-color--a87b2b, #A87B2B);
  stop-opacity: 0;
}

.n5i2-0bvm {
  stop-color: var(--svg-color--b4803a, #B4803A);
}

.n6arjdb9t {
  stop-color: var(--svg-color--674c77, #674C77);
  stop-opacity: 0;
}

.n7i_e3b2c {
  stop-color: var(--svg-color--ffce55, #FFCE55);
  stop-opacity: 0;
}

.ny6n6k9ns {
  stop-color: var(--svg-color--44324e, #44324E);
  stop-opacity: 0;
}

.o3446bisv {
  stop-color: var(--svg-color--614679, #614679);
  stop-opacity: 0;
}

.ogaivek7d {
  stop-color: var(--svg-color--7f7588, #7F7588);
  stop-opacity: 0;
}

.oh7b9b82a {
  stop-color: var(--svg-color--9771b1, #9771B1);
  stop-opacity: 0;
}

.okf7hbbwh {
  stop-color: var(--svg-color--b37c29, #B37C29);
}

.olhq6ogmc {
  stop-color: var(--svg-color--695677, #695677);
}

.p40kqibvx {
  fill-rule: evenodd;
  d: path("M16.078 4.986a9 9 0 1 0 0 18a9 9 0 0 0 0-18m-10 9c0-5.523 4.477-10 10-10s10 4.477 10 10s-4.477 10-10 10s-10-4.477-10-10");
}

.p481wjbcn {
  fill-rule: evenodd;
  d: path("M16.078 8.03a5.957 5.957 0 1 0 0 11.913a5.957 5.957 0 0 0 0-11.914M9.12 13.985a6.957 6.957 0 1 1 13.914 0a6.957 6.957 0 0 1-13.914 0");
}

.p4tqz185x {
  fill-rule: evenodd;
  d: path("M16.578 22.838v-8.844h-1v8.844z");
}

.p8j_j_bxx {
  cx: 16.078px;
  cy: 13.986px;
  r: 2.48px;
}

.q57gsfbfa {
  stop-color: var(--svg-color--e8d3ff, #E8D3FF);
}

.qclsl1bte {
  stop-color: var(--svg-color--a764db, #A764DB);
}

.qu9xdk-_h {
  width: 3.977px;
  height: 3.977px;
  x: 7.062px;
  y: 4.963px;
  rx: 0.7px;
}

.qvs1eybyc {
  stop-color: var(--svg-color--ffe653, #FFE653);
  stop-opacity: 0;
}

.r_6fpcc0q {
  fill: var(--svg-color--814dc5, #814DC5);
  fill-rule: evenodd;
  d: path("m23.841 21.07l-7.576-7.576l-.707.707l7.576 7.576z");
}

.r0jo6i0wx {
  stop-color: var(--svg-color--ffce55, #FFCE55);
}

.r77zsikrk {
  stop-color: var(--svg-color--8e66db, #8E66DB);
}

.r8emc48kl {
  stop-color: var(--svg-color--8b838e, #8B838E);
}

.raalbcg5d {
  fill: var(--svg-color--8d60c4, #8D60C4);
  fill-rule: evenodd;
  d: path("m22.04 7.176l-6.253 6.253l.707.707l6.253-6.253z");
}

.rif8wbcho {
  fill: var(--svg-color--9069bb, #9069BB);
  fill-rule: evenodd;
  d: path("M16.578 5.271v8.844h-1V5.271z");
}

.rjdskei1k {
  stop-color: var(--svg-color--bd6f43, #BD6F43);
  stop-opacity: 0;
}

.rugn9wbne {
  stop-color: var(--svg-color--b4803a, #B4803A);
  stop-opacity: 0;
}

.rwr8rn_nb {
  stop-color: var(--svg-color--ffee59, #FFEE59);
  stop-opacity: 0;
}

.s050q1b5p {
  d: path("M17.82 3.693a.25.25 0 0 1 .25.25V5.33a.7.7 0 0 1-.7.7h-2.577a.7.7 0 0 1-.7-.7V3.943a.25.25 0 0 1 .25-.25z");
}

.s2-mefblg {
  stop-color: var(--svg-color--cb7d3f, #CB7D3F);
}

.sf677-bko {
  fill-rule: evenodd;
  d: path("M25.91 13.384H15.874v1H25.91z");
}

.t_khuvvui {
  stop-color: var(--svg-color--fdf7ff, #FDF7FF);
}

.talb2713b {
  stop-color: var(--svg-color--4c3658, #4C3658);
  stop-opacity: 0;
}

.td0j44bbs {
  stop-color: var(--svg-color--b47c2d, #B47C2D);
  stop-opacity: 0;
}

.td43repzy {
  stop-color: var(--svg-color--a6812d, #A6812D);
  stop-opacity: 0;
}

.tderzlbxz {
  cx: 16.14px;
  cy: 13.986px;
  r: 6.457px;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
}

.tffd3c-pu {
  fill-rule: evenodd;
  d: path("m9.974 7.176l6.254 6.253l-.707.707l-6.254-6.253z");
}

.u_lr15bqk {
  stop-color: var(--svg-color--bcb2c8, #BCB2C8);
}

.ujy6bwoxf {
  stop-color: var(--svg-color--a6812d, #A6812D);
}

.uw1rxccqd {
  stop-color: var(--svg-color--816497, #816497);
}

.uwf77hb5j {
  stop-color: var(--svg-color--736aa5, #736AA5);
  stop-opacity: 0;
}

.v4am1yb9a {
  width: 3.977px;
  height: 3.977px;
  x: 21.117px;
  y: 19.049px;
  rx: 0.7px;
}

.v52v6f_zk {
  stop-color: var(--svg-color--cb7d3f, #CB7D3F);
  stop-opacity: 0;
}

.wn_bnqbvx {
  stop-color: var(--svg-color--9893a0, #9893A0);
  stop-opacity: 0;
}

.x2ge7y1za {
  stop-color: var(--svg-color--dfccf3, #DFCCF3);
}

.x6o2sabtt {
  stop-color: var(--svg-color--b27f32, #B27F32);
  stop-opacity: 0;
}

.xc8zlzbhv {
  fill-rule: evenodd;
  d: path("M16.578 5.271v8.844h-1V5.271z");
}

.xelsirb9t {
  stop-color: var(--svg-color--f4edfa, #F4EDFA);
}

.xhzbhet8v {
  fill: var(--svg-color--9069bb, #9069BB);
  fill-rule: evenodd;
  d: path("m9.974 7.176l6.254 6.253l-.707.707l-6.254-6.253z");
}

.xmgsf_b7p {
  d: path("M24.852 6.607a.25.25 0 0 1 .25.25v1.386a.7.7 0 0 1-.7.7h-2.577a.7.7 0 0 1-.7-.7V6.857a.25.25 0 0 1 .25-.25z");
}

.xsgosw_vs {
  fill: var(--svg-color--f7bd4b, #F7BD4B);
  fill-rule: evenodd;
  d: path("M16.078 8.03a5.957 5.957 0 1 0 0 11.913a5.957 5.957 0 0 0 0-11.914M9.12 13.985a6.957 6.957 0 1 1 13.914 0a6.957 6.957 0 0 1-13.914 0");
}

.xtro7g7do {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M5.914 29.352h20.369");
}

.y-72o53eb {
  stop-color: var(--svg-color--b37c29, #B37C29);
  stop-opacity: 0;
}

.y4_ddpblg {
  stop-color: var(--svg-color--de9347, #DE9347);
  stop-opacity: 0;
}

.y96sd_b-d {
  stop-color: var(--svg-color--f4edfa, #F4EDFA);
  stop-opacity: 0;
}

.ybbew58sb {
  fill: var(--svg-color--9069bb, #9069BB);
  fill-rule: evenodd;
  d: path("M6.105 13.384H16.14v1H6.105z");
}

.ybf2o-bfb {
  fill-rule: evenodd;
  d: path("m8.152 21.07l7.576-7.576l.707.707l-7.576 7.576z");
}

.yhfl73dmd {
  stop-color: var(--svg-color--674c77, #674C77);
}

.ync_4qb8l {
  stop-color: var(--svg-color--de9347, #DE9347);
}

.yvub0oggx {
  d: path("M24.844 20.69a.25.25 0 0 1 .25.25v1.385a.7.7 0 0 1-.7.7h-2.577a.7.7 0 0 1-.7-.7v-1.386a.25.25 0 0 1 .25-.25z");
}

.yvwckabsx {
  stop-color: var(--svg-color--796bb4, #796BB4);
}

.yw4dz90vo {
  fill-rule: evenodd;
  d: path("m23.841 21.07l-7.576-7.576l-.707.707l7.576 7.576z");
}

.zd-glpb3k {
  fill: var(--svg-color--ffcd52, #FFCD52);
  fill-rule: evenodd;
  d: path("M16.078 4.986a9 9 0 1 0 0 18a9 9 0 0 0 0-18m-10 9c0-5.523 4.477-10 10-10s10 4.477 10 10s-4.477 10-10 10s-10-4.477-10-10");
}

.zjcakryiv {
  stop-color: var(--svg-color--fdf7ff, #FDF7FF);
  stop-opacity: 0;
}

.zl8h5lbwr {
  stop-color: var(--svg-color--9673ac, #9673AC);
  stop-opacity: 0;
}

.zmz05ebqc {
  stop-color: var(--svg-color--704d82, #704D82);
}

.znxfl-8gg {
  cx: 16.078px;
  cy: 13.986px;
  r: 2.48px;
  fill: var(--svg-color--ffc952, #FFC952);
}

.zuz4jibbq {
  stop-color: var(--svg-color--ffee59, #FFEE59);
}

.zzgtq8yut {
  stop-color: var(--svg-color--b27f32, #B27F32);
}

</style>
