<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":265};
const content = `<defs><radialGradient id="SVGyidrs6Xz" cx="-7907.187" cy="-8515.121" r="80.797" gradientTransform="translate(26367.938 28186.305)scale(3.3067)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="z0pzm41lc"/><stop offset=".186" class="jqkul5esn"/><stop offset=".247" class="t9z33-8nb"/><stop offset=".283" class="qert0-2pd"/><stop offset=".403" class="k0fj10boc"/><stop offset=".467" class="rvh2s6bnq"/><stop offset=".71" class="y3dbabbby"/><stop offset=".782" class="ujafrpb4h"/><stop offset=".86" class="i9887abso"/></radialGradient><radialGradient id="SVG0IVpgbgM" cx="-7936.711" cy="-8482.089" r="80.797" gradientTransform="translate(26367.938 28186.305)scale(3.3067)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="rf42j1bzb"/><stop offset=".351" class="fuy9xbb1h"/><stop offset=".435" class="d_cylebxq"/><stop offset=".497" class="uw7vv9bgp"/><stop offset=".53" class="zd54yskjb"/></radialGradient><radialGradient id="SVG5bHMjbfc" cx="-7926.97" cy="-8533.457" r="58.534" gradientTransform="translate(26367.938 28186.305)scale(3.3067)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ngihcqxnq"/><stop offset=".252" class="cbprfjcap"/><stop offset=".506" class="gan483yvy"/><stop offset=".526" class="qert0-2pd"/></radialGradient><radialGradient id="SVGEHoaNdMW" cx="-7945.648" cy="-8460.984" r="38.471" gradientTransform="translate(26367.938 28186.305)scale(3.3067)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="qs74n2bxc"/><stop offset=".472" class="sws_7pbde"/><stop offset=".669" class="qx79zlbxq"/><stop offset="1" class="se-bvpjco"/></radialGradient><radialGradient id="SVG6OUB2b6N" cx="-7935.62" cy="-8491.546" r="20.397" gradientTransform="matrix(3.21411 -.77707 .90934 3.76302 33365.914 25904.014)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="xfn17eghk"/><stop offset=".278" class="x1xap4b5i"/><stop offset=".747" class="si-45lzvn"/><stop offset=".975" class="fgqr6cbuk"/></radialGradient><radialGradient id="SVGfyXvUXoB" cx="-7937.731" cy="-8518.427" r="27.676" gradientTransform="translate(26367.938 28186.305)scale(3.3067)" gradientUnits="userSpaceOnUse"><stop offset="0" class="slni1ub0a"/><stop offset=".121" class="rnpsn_wei"/><stop offset=".295" class="tbenpfbzu"/><stop offset=".502" class="z_p-xuugy"/><stop offset=".732" class="sskf33_kx"/><stop offset=".792" class="o-j9s11to"/></radialGradient><radialGradient id="SVGT2ddtPSF" cx="-7915.977" cy="-8535.981" r="118.081" gradientTransform="translate(26367.938 28186.305)scale(3.3067)" gradientUnits="userSpaceOnUse"><stop offset=".113" class="ngihcqxnq"/><stop offset=".456" class="qert0-2pd"/><stop offset=".622" class="vy0edxsbz"/><stop offset=".716" class="yz849_k5q"/><stop offset=".904" class="pa94j0b5i"/></radialGradient><radialGradient id="SVGH7WrGcHb" cx="-7927.165" cy="-8522.859" r="86.499" gradientTransform="matrix(.3472 3.29017 -2.15928 .22816 -15491.597 28008.376)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ngihcqxnq"/><stop offset=".06" class="v0-v_md3s"/><stop offset=".168" class="w5l6hxbiz"/><stop offset=".304" class="qert0-2pd"/><stop offset=".356" class="stemjjb_r"/><stop offset=".455" class="h8gzenb1i"/><stop offset=".57" class="yz849_k5q"/><stop offset=".737" class="pa94j0b5i"/></radialGradient><radialGradient id="SVGLGsqnb9u" cx="-7938.383" cy="-8508.176" r="73.72" gradientTransform="translate(26367.938 28186.305)scale(3.3067)" gradientUnits="userSpaceOnUse"><stop offset=".137" class="ngihcqxnq"/><stop offset=".48" class="qert0-2pd"/><stop offset=".592" class="vy0edxsbz"/><stop offset=".655" class="yz849_k5q"/><stop offset=".904" class="pa94j0b5i"/></radialGradient><radialGradient id="SVGYSHzlc1q" cx="-7918.923" cy="-8503.861" r="80.686" gradientTransform="translate(26367.938 28186.305)scale(3.3067)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="ngihcqxnq"/><stop offset=".231" class="mgj6oyb9z"/><stop offset=".509" class="d9z_-6j1y"/><stop offset=".626" class="qert0-2pd"/></radialGradient><linearGradient id="SVGyUi6ncnI" x1="70.786" x2="6.447" y1="12.393" y2="74.468" gradientTransform="translate(-2.999 -.01)scale(3.3067)" gradientUnits="userSpaceOnUse"><stop offset=".048" class="ngihcqxnq"/><stop offset=".111" class="v0-v_md3s"/><stop offset=".225" class="w5l6hxbiz"/><stop offset=".368" class="qert0-2pd"/><stop offset=".401" class="stemjjb_r"/><stop offset=".462" class="h8gzenb1i"/><stop offset=".534" class="yz849_k5q"/><stop offset=".705" class="pa94j0b5i"/></linearGradient><linearGradient id="SVG1UrWScUt" x1="70.013" x2="15.267" y1="12.061" y2="66.806" gradientTransform="translate(-2.999 -.01)scale(3.3067)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="rkbutcc1z"/><stop offset=".266" class="u-xjwebda"/><stop offset=".489" class="qovj58-ls"/><stop offset=".6" class="rb4_ys4wj"/></linearGradient></defs><path fill="url(#SVGyUi6ncnI)" class="fcri_dbnf"/><path fill="url(#SVGyidrs6Xz)" class="x9enaew3q"/><path fill="url(#SVG0IVpgbgM)" class="x9enaew3q"/><path fill="url(#SVG5bHMjbfc)" class="tv1lhjbhv"/><path fill="url(#SVGEHoaNdMW)" class="qm1hrlbor"/><path fill="url(#SVG6OUB2b6N)" class="qm1hrlbor"/><path fill="url(#SVGfyXvUXoB)" class="ohu5nwblx"/><path fill="url(#SVGT2ddtPSF)" class="d_jfz36me"/><path fill="url(#SVGH7WrGcHb)" class="fhhp-hbdr"/><path fill="url(#SVGLGsqnb9u)" class="p9y4etb8i"/><path fill="url(#SVGYSHzlc1q)" class="v15xg7i0r"/><path fill="url(#SVG1UrWScUt)" class="jrj87pb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:firefox" /></template>
<style>
.cbprfjcap {
  stop-color: var(--svg-color--ffdc3e, #ffdc3e);
}

.d_cylebxq {
  stop-color: var(--svg-color--db293d, #db293d);
  stop-opacity: 0.343;
}

.d_jfz36me {
  d: path("M2.471 139.411c9.89 58.443 62.857 103.063 122.989 104.766c55.652 1.574 91.205-30.732 105.894-62.248a116.07 116.07 0 0 0 3.988-86.497v-.122c0-.096-.02-.153 0-.123l.023.215c4.547 29.684-10.552 58.443-34.155 77.889l-.073.166c-45.989 37.455-90.002 22.598-98.91 16.533a65 65 0 0 1-1.865-.929c-26.814-12.817-37.891-37.247-35.517-58.198a32.91 32.91 0 0 1-30.359-19.096a48.34 48.34 0 0 1 47.117-1.891a63.82 63.82 0 0 0 48.119 1.891c-.049-1.042-22.353-9.92-31.05-18.484c-4.646-4.58-6.851-6.786-8.805-8.442a38 38 0 0 0-3.307-2.507c-.761-.519-1.617-1.081-2.645-1.756c-9.348-6.078-27.939-5.744-28.554-5.727h-.059c-5.079-6.438-4.722-27.667-4.431-32.101a23 23 0 0 0-4.279 2.271a93.4 93.4 0 0 0-12.526 10.73a112 112 0 0 0-12.03 14.342v.019v-.023A108.3 108.3 0 0 0 4.841 108.92c-.062.261-4.616 20.167-2.37 30.491");
}

.d9z_-6j1y {
  stop-color: var(--svg-color--ffaf1e, #ffaf1e);
}

.fcri_dbnf {
  d: path("M248.033 88.713c-5.569-13.399-16.864-27.866-25.71-32.439a133.2 133.2 0 0 1 12.979 38.9l.023.215c-14.49-36.126-39.062-50.692-59.13-82.41a155 155 0 0 1-3.019-4.907a41 41 0 0 1-1.412-2.645a23.3 23.3 0 0 1-1.912-5.076a.33.33 0 0 0-.291-.331a.5.5 0 0 0-.241 0c-.016 0-.043.03-.063.037s-.063.036-.092.049l.049-.086c-32.19 18.849-43.113 53.741-44.118 71.194a64.1 64.1 0 0 0-35.269 13.593a38 38 0 0 0-3.307-2.506a59.4 59.4 0 0 1-.36-31.324a94.9 94.9 0 0 0-30.848 23.841h-.06c-5.079-6.438-4.722-27.667-4.431-32.102a23 23 0 0 0-4.279 2.272a93.4 93.4 0 0 0-12.526 10.73a112 112 0 0 0-11.98 14.375v.019v-.023A108.3 108.3 0 0 0 4.841 108.92l-.171.846a204 204 0 0 0-1.26 8.003c0 .096-.02.185-.03.281a122 122 0 0 0-2.08 17.667v.662c.086 98.661 106.944 160.23 192.344 110.825a128.17 128.17 0 0 0 62.12-89.153c.215-1.653.39-3.29.582-4.96a131.8 131.8 0 0 0-8.313-64.378M100.322 189.031c.599.288 1.161.599 1.776.873l.089.057a69 69 0 0 1-1.865-.93m135.013-93.612v-.123l.023.136z");
}

.fgqr6cbuk {
  stop-color: var(--svg-color--6e008b, #6e008b);
  stop-opacity: 0.6;
}

.fhhp-hbdr {
  d: path("M174.654 88.838a69.8 69.8 0 0 1 11.904 15.542a27 27 0 0 1 1.921 1.574c29.056 26.784 13.832 64.646 12.698 67.341c23.603-19.447 38.688-48.205 34.155-77.89c-14.497-36.142-39.069-50.708-59.137-82.426a155 155 0 0 1-3.019-4.907a41 41 0 0 1-1.412-2.645a23.3 23.3 0 0 1-1.912-5.076a.33.33 0 0 0-.291-.331a.5.5 0 0 0-.241 0c-.016 0-.043.03-.063.037s-.063.036-.092.049c-4.957 2.351-34.35 48.893 5.489 88.732");
}

.fuy9xbb1h {
  stop-color: var(--svg-color--b11927, #b11927);
  stop-opacity: 0.74;
}

.gan483yvy {
  stop-color: var(--svg-color--ff9d12, #ff9d12);
}

.h8gzenb1i {
  stop-color: var(--svg-color--ff672a, #ff672a);
}

.i9887abso {
  stop-color: var(--svg-color--e50080, #e50080);
}

.jqkul5esn {
  stop-color: var(--svg-color--ffac31, #ffac31);
}

.jrj87pb5n {
  d: path("M248.033 88.713c-5.569-13.399-16.864-27.866-25.71-32.439a133.2 133.2 0 0 1 12.979 38.9l.023.215c-14.49-36.126-39.062-50.692-59.13-82.41a155 155 0 0 1-3.019-4.907a41 41 0 0 1-1.412-2.645a23.3 23.3 0 0 1-1.912-5.076a.33.33 0 0 0-.291-.331a.5.5 0 0 0-.241 0c-.016 0-.043.03-.063.037s-.063.036-.092.049l.049-.086c-32.19 18.849-43.113 53.741-44.118 71.194c1.495-.103 2.976-.229 4.504-.229a64.68 64.68 0 0 1 56.154 32.793a44.24 44.24 0 0 0-30.901-7.503c46.096 23.048 33.729 102.415-30.154 99.419a57 57 0 0 1-16.675-3.217a67 67 0 0 1-3.763-1.541c-.724-.331-1.449-.661-2.163-1.032l.089.057a69 69 0 0 1-1.865-.93c.599.288 1.161.599 1.776.873c-15.65-8.088-28.573-23.378-30.187-41.942c0 0 5.916-22.046 42.359-22.046c3.938 0 15.211-10.994 15.413-14.182c-.05-1.042-22.354-9.92-31.05-18.485c-4.646-4.579-6.852-6.785-8.806-8.442a38 38 0 0 0-3.307-2.506a59.4 59.4 0 0 1-.36-31.324a94.9 94.9 0 0 0-30.848 23.841h-.06c-5.079-6.438-4.722-27.667-4.431-32.102a23 23 0 0 0-4.279 2.272a93.4 93.4 0 0 0-12.526 10.73a112 112 0 0 0-11.98 14.375v.019v-.023A108.3 108.3 0 0 0 4.841 108.92l-.171.846c-.242 1.128-1.323 6.855-1.479 8.085c0 .093 0-.096 0 0A149 149 0 0 0 1.3 135.717v.662c.086 98.661 106.944 160.23 192.344 110.825a128.17 128.17 0 0 0 62.12-89.153c.215-1.653.39-3.29.582-4.96a131.8 131.8 0 0 0-8.313-64.378m-12.715 6.583l.024.136z");
}

.k0fj10boc {
  stop-color: var(--svg-color--ff563b, #ff563b);
}

.mgj6oyb9z {
  stop-color: var(--svg-color--ffe141, #ffe141);
}

.ngihcqxnq {
  stop-color: var(--svg-color--fff44f, #fff44f);
}

.o-j9s11to {
  stop-color: var(--svg-color--ff7139, #ff7139);
}

.ohu5nwblx {
  d: path("M83.852 80.545a82 82 0 0 1 2.645 1.756a59.4 59.4 0 0 1-.36-31.324a94.9 94.9 0 0 0-30.849 23.841c.625-.017 19.216-.351 28.564 5.727");
}

.p9y4etb8i {
  d: path("M188.459 105.937a27 27 0 0 0-1.921-1.574c-.261-.195-.519-.39-.797-.585a44.24 44.24 0 0 0-30.901-7.503c46.095 23.048 33.728 102.415-30.154 99.419a57 57 0 0 1-16.675-3.217a67 67 0 0 1-3.763-1.541c-.725-.331-1.449-.661-2.163-1.032l.089.057c8.908 6.081 52.907 20.938 98.91-16.534l.073-.165c1.147-2.679 16.371-40.55-12.698-67.325");
}

.pa94j0b5i {
  stop-color: var(--svg-color--e31587, #e31587);
}

.qert0-2pd {
  stop-color: var(--svg-color--ff980e, #ff980e);
}

.qm1hrlbor {
  d: path("M129.683 111.734c-.212 3.188-11.475 14.182-15.413 14.182c-36.443 0-42.359 22.046-42.359 22.046c1.614 18.564 14.55 33.854 30.187 41.942c.714.371 1.439.705 2.163 1.032a71 71 0 0 0 3.763 1.541a57 57 0 0 0 16.675 3.217c63.876 2.996 76.25-76.384 30.154-99.419a44.24 44.24 0 0 1 30.901 7.503A64.68 64.68 0 0 0 129.6 70.985c-1.521 0-3.009.126-4.504.229a64.1 64.1 0 0 0-35.269 13.593c1.954 1.654 4.16 3.863 8.806 8.442c8.696 8.568 31 17.443 31.05 18.485");
}

.qovj58-ls {
  stop-color: var(--svg-color--fff44f, #fff44f);
  stop-opacity: 0.217;
}

.qs74n2bxc {
  stop-color: var(--svg-color--3a8ee6, #3a8ee6);
}

.qx79zlbxq {
  stop-color: var(--svg-color--9059ff, #9059ff);
}

.rb4_ys4wj {
  stop-color: var(--svg-color--fff44f, #fff44f);
  stop-opacity: 0;
}

.rf42j1bzb {
  stop-color: var(--svg-color--960e18, #960e18);
}

.rkbutcc1z {
  stop-color: var(--svg-color--fff44f, #fff44f);
  stop-opacity: 0.8;
}

.rnpsn_wei {
  stop-color: var(--svg-color--ffdb27, #ffdb27);
}

.rvh2s6bnq {
  stop-color: var(--svg-color--ff3750, #ff3750);
}

.se-bvpjco {
  stop-color: var(--svg-color--c139e6, #c139e6);
}

.si-45lzvn {
  stop-color: var(--svg-color--7716a8, #7716a8);
  stop-opacity: 0.45;
}

.slni1ub0a {
  stop-color: var(--svg-color--ffe226, #ffe226);
}

.sskf33_kx {
  stop-color: var(--svg-color--ff7e37, #ff7e37);
}

.stemjjb_r {
  stop-color: var(--svg-color--ff8b16, #ff8b16);
}

.sws_7pbde {
  stop-color: var(--svg-color--5c79f0, #5c79f0);
}

.t9z33-8nb {
  stop-color: var(--svg-color--ff9d17, #ff9d17);
}

.tbenpfbzu {
  stop-color: var(--svg-color--ffc82a, #ffc82a);
}

.tv1lhjbhv {
  d: path("M185.754 103.778c.278.195.536.39.797.585a69.8 69.8 0 0 0-11.904-15.525C134.815 48.999 164.208 2.457 169.165.093l.049-.073c-32.19 18.849-43.113 53.741-44.118 71.194c1.495-.103 2.976-.229 4.504-.229a64.68 64.68 0 0 1 56.154 32.793");
}

.u-xjwebda {
  stop-color: var(--svg-color--fff44f, #fff44f);
  stop-opacity: 0.634;
}

.ujafrpb4h {
  stop-color: var(--svg-color--eb0878, #eb0878);
}

.uw7vv9bgp {
  stop-color: var(--svg-color--f5334b, #f5334b);
  stop-opacity: 0.094;
}

.v0-v_md3s {
  stop-color: var(--svg-color--ffe847, #ffe847);
}

.v15xg7i0r {
  d: path("M71.911 147.962s5.916-22.046 42.359-22.046c3.938 0 15.211-10.994 15.413-14.182a63.82 63.82 0 0 1-48.119-1.892a48.34 48.34 0 0 0-47.118 1.892a32.91 32.91 0 0 0 30.359 19.096c-2.374 20.955 8.703 45.385 35.517 58.198c.599.288 1.161.599 1.776.873c-15.65-8.085-28.573-23.375-30.187-41.939");
}

.vy0edxsbz {
  stop-color: var(--svg-color--ff5634, #ff5634);
}

.w5l6hxbiz {
  stop-color: var(--svg-color--ffc830, #ffc830);
}

.x1xap4b5i {
  stop-color: var(--svg-color--8c4ff3, #8c4ff3);
  stop-opacity: 0.064;
}

.x9enaew3q {
  d: path("M248.033 88.713c-5.569-13.399-16.864-27.866-25.71-32.439a133.2 133.2 0 0 1 12.979 38.9v.122l.023.136a116.07 116.07 0 0 1-3.988 86.497c-14.688 31.516-50.242 63.819-105.894 62.248c-60.132-1.703-113.089-46.323-122.989-104.766c-1.802-9.216 0-13.888.906-21.378a95.4 95.4 0 0 0-2.06 17.684v.662c.086 98.661 106.944 160.23 192.344 110.825a128.17 128.17 0 0 0 62.12-89.153c.215-1.653.39-3.29.582-4.96a131.8 131.8 0 0 0-8.313-64.378");
}

.xfn17eghk {
  stop-color: var(--svg-color--9059ff, #9059ff);
  stop-opacity: 0;
}

.y3dbabbby {
  stop-color: var(--svg-color--f5156c, #f5156c);
}

.yz849_k5q {
  stop-color: var(--svg-color--ff3647, #ff3647);
}

.z_p-xuugy {
  stop-color: var(--svg-color--ffa930, #ffa930);
}

.z0pzm41lc {
  stop-color: var(--svg-color--ffbd4f, #ffbd4f);
}

.zd54yskjb {
  stop-color: var(--svg-color--ff3750, #ff3750);
  stop-opacity: 0;
}

</style>
