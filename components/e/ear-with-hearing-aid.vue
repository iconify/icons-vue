<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="be_9vcbvu"/><g filter="url(#iED9DUK)"><ellipse fill="url(#iCRczld)" transform="rotate(26.087 16.657 9.426)" class="x4aq_ubdm"/></g><g filter="url(#iBg1dQd)"><path fill="url(#i77x4sc)" class="bs35zwbcq"/><path fill="url(#ixvnoge)" class="bs35zwbcq"/></g><g filter="url(#irXcuHc)"><circle fill="url(#iUYDBYd)" class="ig8_klbjg"/></g><path class="dar3rdxtc"/><circle fill="url(#i9RpICB)" class="z3uqb2b7i"/><circle fill="url(#i72mfBG)" class="z3uqb2b7i"/><g filter="url(#ikklE6d)"><circle class="jhvj3acwi"/></g><g filter="url(#i4bFumd)"><path fill="url(#ivChInb)" class="xi9284smk"/><path fill="url(#i8UJ7Kd)" class="xi9284smk"/></g><path fill="url(#iDINSoR)" class="xi9284smk"/><path fill="url(#iwouEyG)" class="xi9284smk"/><path fill="url(#ilS1CAJ)" class="xi9284smk"/><path fill="url(#i6eqwxe)" class="xi9284smk"/><path fill="url(#ipU2SMe)" class="xi9284smk"/><g filter="url(#i1Mgjhc)"><path stroke="url(#iqxwBtd)" class="tjt7gjb5p"/></g><g filter="url(#i4Q3q8U)"><path stroke="url(#isY4RJe)" class="euq-e6dxp"/></g><rect fill="url(#i6meFOc)" class="hvln_f2fh"/><rect fill="url(#iDc9lcc)" class="vyox7dbyj"/><rect fill="url(#i6N0T3d)" class="vyox7dbyj"/><g filter="url(#iO5qP1d)"><path class="d6l7gwbxy"/><path fill="url(#itkDLEe)" class="qdd2-vz8a"/></g><path class="bldttub1p"/><path fill="url(#icCyKub)" class="zj5bk04dp"/><path fill="url(#ilRC28c)" class="zj5bk04dp"/><path fill="url(#iIbREJd)" class="zj5bk04dp"/><path fill="url(#it1gvGc)" class="mdmzdbdgm"/><g filter="url(#iVIDBUd)"><path stroke="url(#i8CJBNd)" class="woyu-piuz"/></g><g filter="url(#iCCxoSj)"><path stroke="url(#iq10ITb)" class="y_1bn3bos"/></g><g filter="url(#iKSHJgd)"><path stroke="url(#idqEInd)" class="ecqt2zrqa"/></g><g filter="url(#iFvk1kb)"><path fill="url(#iVRAwYd)" class="waxgswb4e"/></g><defs><linearGradient id="i77x4sc" x1="12.353" x2="9.697" y1="12.799" y2="18.194" gradientUnits="userSpaceOnUse"><stop class="b00s7bcmy"/><stop offset="1" class="if_yphb0b"/></linearGradient><linearGradient id="ixvnoge" x1="13.016" x2="14.944" y1="27.203" y2="21.809" gradientUnits="userSpaceOnUse"><stop offset=".218" class="gips64bhy"/><stop offset="1" class="uf4yr6jab"/></linearGradient><linearGradient id="iUYDBYd" x1="14.056" x2="12.023" y1="20.467" y2="24.046" gradientUnits="userSpaceOnUse"><stop offset=".34" class="idibcljtc"/><stop offset="1" class="a0x44vbjn"/></linearGradient><linearGradient id="i9RpICB" x1="11.273" x2="11.273" y1="19.128" y2="24.913" gradientUnits="userSpaceOnUse"><stop class="lx_jvtb1l"/><stop offset="1" class="on-xd39ns"/></linearGradient><linearGradient id="ivChInb" x1="11.087" x2="19.223" y1="31.061" y2="-.158" gradientUnits="userSpaceOnUse"><stop class="bmggupupr"/><stop offset="1" class="wgpnrcbke"/></linearGradient><linearGradient id="iqxwBtd" x1="24.017" x2="16.875" y1="11.504" y2="3.97" gradientUnits="userSpaceOnUse"><stop class="dpqjfnyxb"/><stop offset=".51" class="o06vv8bvy"/><stop offset="1" class="dpqjfnyxb"/></linearGradient><linearGradient id="isY4RJe" x1="7.953" x2="20.43" y1="2.614" y2="23.93" gradientUnits="userSpaceOnUse"><stop class="dpqjfnyxb"/><stop offset=".698" class="o06vv8bvy"/></linearGradient><linearGradient id="i6meFOc" x1="26.977" x2="26.977" y1="10.595" y2="15.55" gradientUnits="userSpaceOnUse"><stop class="kdl2hbbyb"/><stop offset="1" class="p4a1uebzz"/></linearGradient><linearGradient id="iDc9lcc" x1="27.514" x2="27.514" y1="15.81" y2="14.697" gradientUnits="userSpaceOnUse"><stop class="d7eywim1k"/><stop offset="1" class="sqji9tbob"/></linearGradient><linearGradient id="i6N0T3d" x1="26.977" x2="26.977" y1="10.519" y2="10.988" gradientUnits="userSpaceOnUse"><stop class="eu-87q5qq"/><stop offset="1" class="e14ccpbpi"/></linearGradient><linearGradient id="iIbREJd" x1="22.782" x2="22.782" y1="19.98" y2="17.334" gradientUnits="userSpaceOnUse"><stop class="nf1xib-zk"/><stop offset="1" class="stmsp0bcc"/></linearGradient><linearGradient id="i8CJBNd" x1="14.755" x2="6.598" y1="2.013" y2="9.06" gradientUnits="userSpaceOnUse"><stop class="ne07wgnjt"/><stop offset=".551" class="fkqbx3b-n"/><stop offset="1" class="ne07wgnjt"/></linearGradient><linearGradient id="iq10ITb" x1="6.16" x2="10.108" y1="13.371" y2="18.002" gradientUnits="userSpaceOnUse"><stop class="ne07wgnjt"/><stop offset=".551" class="fkqbx3b-n"/><stop offset="1" class="ne07wgnjt"/></linearGradient><linearGradient id="idqEInd" x1="16.341" x2="30.529" y1="2.31" y2="7.516" gradientUnits="userSpaceOnUse"><stop class="h5tsjybzx"/><stop offset=".123" class="sd9-1cnwp"/><stop offset=".542" class="iab0nwb4s"/><stop offset=".763" class="borhhobgo"/></linearGradient><linearGradient id="iVRAwYd" x1="27.637" x2="27.637" y1="9.746" y2="14.824" gradientUnits="userSpaceOnUse"><stop offset=".152" class="g4udvybro"/><stop offset=".5" class="m_f0evbyx"/><stop offset="1" class="g4udvybro"/></linearGradient><radialGradient id="iCRczld" cx="0" cy="0" r="1" gradientTransform="rotate(-90.156 15.265 -1.35)scale(7.89895 13.7759)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="r_u_h5b3s"/><stop offset=".848" class="n64k1un-r"/></radialGradient><radialGradient id="i72mfBG" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 4.08 12.487)scale(3.12583 3.56972)" gradientUnits="userSpaceOnUse"><stop class="t5l7i-35d"/><stop offset="1" class="adrn92bkz"/></radialGradient><radialGradient id="i8UJ7Kd" cx="0" cy="0" r="1" gradientTransform="matrix(3.73663 -5.36387 6.00566 4.18372 16.813 11.112)" gradientUnits="userSpaceOnUse"><stop offset=".478" class="x6vt38irh"/><stop offset="1" class="tmjf1_bjl"/></radialGradient><radialGradient id="iDINSoR" cx="0" cy="0" r="1" gradientTransform="matrix(.13826 -4.4596 5.9153 .1834 22.34 15.39)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="lz69ozbxw"/><stop offset="1" class="vze3y573s"/></radialGradient><radialGradient id="iwouEyG" cx="0" cy="0" r="1" gradientTransform="rotate(115.159 1.488 16.884)scale(4.79259 4.67362)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="ugx2oqlqp"/><stop offset="1" class="pnq4imboc"/></radialGradient><radialGradient id="ilS1CAJ" cx="0" cy="0" r="1" gradientTransform="matrix(-11.08937 -22.84172 16.6494 -8.08308 21.755 26.179)" gradientUnits="userSpaceOnUse"><stop offset=".953" class="ctwlg2kbz"/><stop offset="1" class="nooxnls9a"/></radialGradient><radialGradient id="i6eqwxe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.02789 21.09763 -16.47054 -2.36382 14 8.367)" gradientUnits="userSpaceOnUse"><stop offset=".912" class="iax6gzb3y"/><stop offset="1" class="nogxpdbja"/></radialGradient><radialGradient id="ipU2SMe" cx="0" cy="0" r="1" gradientTransform="matrix(2.01899 0 0 3.58596 9.912 22.02)" gradientUnits="userSpaceOnUse"><stop class="yegc_ubts"/><stop offset=".975" class="kjygdhcvm"/></radialGradient><radialGradient id="itkDLEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.78125 1.10077 0 9.801 18.793)" gradientUnits="userSpaceOnUse"><stop class="cizba4bqb"/><stop offset="1" class="gme4zsb3v"/></radialGradient><radialGradient id="icCyKub" cx="0" cy="0" r="1" gradientTransform="matrix(6.96874 4.09377 -2.53183 4.30988 16.817 2.995)" gradientUnits="userSpaceOnUse"><stop class="p9rps_sqh"/><stop offset="1" class="bfgxzgb-n"/></radialGradient><radialGradient id="ilRC28c" cx="0" cy="0" r="1" gradientTransform="matrix(5.39882 .43865 -.8355 10.28301 20.477 14.84)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="oniokeg5c"/><stop offset="1" class="wnrg0_btk"/></radialGradient><radialGradient id="it1gvGc" cx="0" cy="0" r="1" gradientTransform="rotate(157.557 4.218 10.92)scale(2.33294 1.92272)" gradientUnits="userSpaceOnUse"><stop class="bpzyi6xnk"/><stop offset="1" class="w74yu-sct"/></radialGradient><filter id="iED9DUK" width="15.216" height="12.151" x="9.049" y="3.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4715" stdDeviation=".5"/></filter><filter id="iBg1dQd" width="12.12" height="17.122" x="7.182" y="11.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4715" stdDeviation=".25"/></filter><filter id="irXcuHc" width="7.14" height="7.14" x="8.213" y="18.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4715" stdDeviation=".375"/></filter><filter id="ikklE6d" width="6.047" height="6.047" x="8.267" y="19.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4715" stdDeviation=".25"/></filter><filter id="i4bFumd" width="18.421" height="26.794" x="6.406" y="2.67" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.6 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4715"/></filter><filter id="i1Mgjhc" width="11.841" height="12.383" x="13.772" y="1.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4715" stdDeviation=".75"/></filter><filter id="i4Q3q8U" width="12.757" height="21.677" x="6.426" y="8.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4715" stdDeviation=".75"/></filter><filter id="iO5qP1d" width="10.696" height="17.149" x="5.535" y="1.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4715"/></filter><filter id="iVIDBUd" width="8.725" height="7.879" x="6.048" y="2.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4715" stdDeviation=".1"/></filter><filter id="iCCxoSj" width="4.898" height="4.897" x="5.734" y="12.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4715" stdDeviation=".1"/></filter><filter id="iKSHJgd" width="10.143" height="7.663" x="16.163" y="1.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4715" stdDeviation=".15"/></filter><filter id="iFvk1kb" width=".797" height="4.25" x="27.239" y="10.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4715" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ear-with-hearing-aid" /></template>
<style>
.a0x44vbjn {
  stop-color: var(--svg-color--c97a03, #C97A03);
}

.adrn92bkz {
  stop-color: var(--svg-color--ffe663, #FFE663);
  stop-opacity: 0;
}

.b00s7bcmy {
  stop-color: var(--svg-color--e58403, #E58403);
}

.be_9vcbvu {
  fill: var(--svg-color--ffc94c, #FFC94C);
  d: path("M6.406 23.264c0 3.125 2.489 5.959 5.659 6.2c2.284 0 4.299-1.325 5.252-3.104l5.55-9.827A8.96 8.96 0 1 0 6.406 11.63z");
}

.bfgxzgb-n {
  stop-color: var(--svg-color--959595, #959595);
  stop-opacity: 0;
}

.bldttub1p {
  fill: var(--svg-color--cecad1, #CECAD1);
  d: path("M15.981 2.687c4.482.307 8.086 3.903 8.32 8.402c0 2.077-.218 3.438-1.468 5.516l-1.657 2.938h2.602a3.25 3.25 0 0 0 3.25-3.25v-3.875c0-3.324-3.838-10.45-10.841-10.731a.2.2 0 0 0-.206.198z");
}

.bmggupupr {
  stop-color: var(--svg-color--f0a130, #F0A130);
}

.borhhobgo {
  stop-color: var(--svg-color--dadada, #DADADA);
  stop-opacity: 0;
}

.bpzyi6xnk {
  stop-color: var(--svg-color--cec8c7, #CEC8C7);
}

.bs35zwbcq {
  d: path("M12.065 28.379c-3.17-.242-4.383-1.99-4.383-5.116V12.409l2.26-.151l8.86 8.83l-2.833 4.79c-.954 1.78-1.62 2.502-3.904 2.502");
}

.cizba4bqb {
  stop-color: var(--svg-color--635951, #635951);
}

.ctwlg2kbz {
  stop-color: var(--svg-color--cea561, #CEA561);
  stop-opacity: 0;
}

.d6l7gwbxy {
  fill: var(--svg-color--bfbdbd, #BFBDBD);
  d: path("M5.536 11.07v.003q.015 1.125 0 2.25c-.016 1.25.66 2.114.973 2.38c.607.547 1.475.848 2.218 1.105c.438.152 1.152.438 1.152.969v.8l.93-.316c0-.508-.023-.985-.187-1.273c-.367-.645-.82-1.07-2.446-1.531a2.32 2.32 0 0 1-1.718-2.008v-2.35h.001c.245-4.705 4.137-8.43 8.903-8.43q.312 0 .62.022v-.815a.197.197 0 0 0-.197-.198c-5.13-.007-10.226 3.87-10.25 9.392");
}

.d7eywim1k {
  stop-color: var(--svg-color--917ea4, #917EA4);
}

.dar3rdxtc {
  stroke: var(--svg-color--000, #000);
  d: path("M16.813 3.85c1.858.26 5.761 1.88 6.509 6.268");
}

.dpqjfnyxb {
  stop-color: var(--svg-color--ffed65, #FFED65);
  stop-opacity: 0;
}

.e14ccpbpi {
  stop-color: var(--svg-color--bbb, #BBB);
  stop-opacity: 0;
}

.ecqt2zrqa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.563 2.31c2.44.332 6.964 1.608 9.343 6.863");
}

.eu-87q5qq {
  stop-color: var(--svg-color--bbb, #BBB);
}

.euq-e6dxp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.676 10.54v13.168c.021.864.322 3.287 2.954 3.887c2.215.506 3.495-.663 4.122-1.838l1.181-2.049");
}

.fkqbx3b-n {
  stop-color: var(--svg-color--d3cdcf, #D3CDCF);
}

.ft5dv1b6b {
  fill: none;
}

.g4udvybro {
  stop-color: var(--svg-color--ecebed, #ECEBED);
  stop-opacity: 0;
}

.gips64bhy {
  stop-color: var(--svg-color--e2992f, #E2992F);
}

.gme4zsb3v {
  stop-color: var(--svg-color--635951, #635951);
  stop-opacity: 0;
}

.h5tsjybzx {
  stop-color: var(--svg-color--a29f9f, #A29F9F);
  stop-opacity: 0;
}

.hvln_f2fh {
  width: 2.016px;
  height: 4.955px;
  x: 25.969px;
  y: 10.595px;
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 0.5px;
}

.iab0nwb4s {
  stop-color: var(--svg-color--dadada, #DADADA);
}

.iax6gzb3y {
  stop-color: var(--svg-color--d98286, #D98286);
  stop-opacity: 0;
}

.idibcljtc {
  stop-color: var(--svg-color--ffe15b, #FFE15B);
}

.if_yphb0b {
  stop-color: var(--svg-color--e58403, #E58403);
  stop-opacity: 0;
}

.ig8_klbjg {
  cx: 11.783px;
  cy: 22.094px;
  r: 2.82px;
}

.jhvj3acwi {
  cx: 11.291px;
  cy: 22.186px;
  r: 2.524px;
  fill: var(--svg-color--ffc947, #FFC947);
}

.kdl2hbbyb {
  stop-color: var(--svg-color--cacaca, #CACACA);
}

.kjygdhcvm {
  stop-color: var(--svg-color--ffcd49, #FFCD49);
  stop-opacity: 0;
}

.lx_jvtb1l {
  stop-color: var(--svg-color--ffc609, #FFC609);
}

.lz69ozbxw {
  stop-color: var(--svg-color--ffcc4c, #FFCC4C);
}

.m_f0evbyx {
  stop-color: var(--svg-color--ecebed, #ECEBED);
}

.mdmzdbdgm {
  d: path("M9.88 19.485a2.9 2.9 0 0 1 1.393-.357c.883 0 1.673.395 2.204 1.02a2.318 2.318 0 0 0-3.598-1.86z");
}

.n64k1un-r {
  stop-color: var(--svg-color--ee8820, #EE8820);
}

.ne07wgnjt {
  stop-color: var(--svg-color--d3cdcf, #D3CDCF);
  stop-opacity: 0;
}

.nf1xib-zk {
  stop-color: var(--svg-color--7b608b, #7B608B);
}

.nogxpdbja {
  stop-color: var(--svg-color--d98286, #D98286);
}

.nooxnls9a {
  stop-color: var(--svg-color--cea561, #CEA561);
}

.o06vv8bvy {
  stop-color: var(--svg-color--ffed65, #FFED65);
}

.on-xd39ns {
  stop-color: var(--svg-color--fea70c, #FEA70C);
}

.oniokeg5c {
  stop-color: var(--svg-color--a08d8d, #A08D8D);
}

.p4a1uebzz {
  stop-color: var(--svg-color--a59eae, #A59EAE);
}

.p9rps_sqh {
  stop-color: var(--svg-color--797979, #797979);
}

.pnq4imboc {
  stop-color: var(--svg-color--ffca4d, #FFCA4D);
  stop-opacity: 0;
}

.qdd2-vz8a {
  d: path("M5.536 11.07v.003q.015 1.125 0 2.25c-.016 1.25.66 2.114.973 2.38c.607.547 1.475.848 2.218 1.105c.438.152 1.152.438 1.152.969v.8l.93-.316c0-.508-.023-.985-.187-1.273c-.367-.645-.82-1.07-2.446-1.531a2.32 2.32 0 0 1-1.718-2.008v-2.35h.001c.245-4.705 4.137-8.43 8.903-8.43q.312 0 .62.022v-.815a.197.197 0 0 0-.197-.198c-5.13-.007-10.226 3.87-10.25 9.392");
}

.r_u_h5b3s {
  stop-color: var(--svg-color--ee8820, #EE8820);
  stop-opacity: 0;
}

.sd9-1cnwp {
  stop-color: var(--svg-color--bebdbc, #BEBDBC);
}

.sqji9tbob {
  stop-color: var(--svg-color--917ea4, #917EA4);
  stop-opacity: 0;
}

.stmsp0bcc {
  stop-color: var(--svg-color--806693, #806693);
  stop-opacity: 0;
}

.t5l7i-35d {
  stop-color: var(--svg-color--ffe663, #FFE663);
}

.tjt7gjb5p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.273 4.12c2.21.362 6.671 2.345 6.84 7.384");
}

.tmjf1_bjl {
  stop-color: var(--svg-color--f49419, #F49419);
  stop-opacity: 0;
}

.uf4yr6jab {
  stop-color: var(--svg-color--e2992f, #E2992F);
  stop-opacity: 0;
}

.ugx2oqlqp {
  stop-color: var(--svg-color--ffca4d, #FFCA4D);
}

.vyox7dbyj {
  width: 2.016px;
  height: 4.955px;
  x: 25.969px;
  y: 10.595px;
  rx: 0.5px;
}

.vze3y573s {
  stop-color: var(--svg-color--ffcc4c, #FFCC4C);
  stop-opacity: 0;
}

.w74yu-sct {
  stop-color: var(--svg-color--a99d99, #A99D99);
}

.waxgswb4e {
  d: path("M27.489 11.074h.297v3.75h-.297z");
}

.wgpnrcbke {
  stop-color: var(--svg-color--ffd135, #FFD135);
}

.wnrg0_btk {
  stop-color: var(--svg-color--a08d8d, #A08D8D);
  stop-opacity: 0;
}

.woyu-piuz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.473 2.31c-1.969.115-7.172 1.748-8.125 7.28");
}

.x4aq_ubdm {
  cx: 16.657px;
  cy: 9.426px;
  rx: 7.02px;
  ry: 4.486px;
}

.x6vt38irh {
  stop-color: var(--svg-color--f49419, #F49419);
}

.xi9284smk {
  d: path("M17.456 22.555a1.736 1.736 0 0 0-2.352.665l-.828 1.466l-.018.034c-.353.658-1.114 1.27-2.059 1.27c-1.21 0-2.322-1.378-2.322-2.726V11.63a5.489 5.489 0 1 1 10.912.86c-.142.905.121 1.902.909 2.372c.867.517 2.009.202 2.286-.77A8.96 8.96 0 1 0 6.406 11.63v11.634c0 3.125 2.489 5.959 5.659 6.2c2.284 0 4.299-1.325 5.252-3.104l.81-1.433a1.736 1.736 0 0 0-.671-2.372");
}

.y_1bn3bos {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.036 13.261c-.021.542.165 1.853 1.578 2.453c1.765.75 2.656.829 2.718 1.844");
}

.yegc_ubts {
  stop-color: var(--svg-color--ffcd49, #FFCD49);
}

.z3uqb2b7i {
  cx: 11.273px;
  cy: 22.021px;
  r: 2.893px;
}

.zj5bk04dp {
  d: path("M15.981 2.687c4.482.307 8.086 3.903 8.32 8.402c0 2.077-.218 3.438-1.468 5.516l-1.657 2.938h2.602a3.25 3.25 0 0 0 3.25-3.25v-3.875c0-3.324-3.838-10.45-10.841-10.731a.2.2 0 0 0-.206.198z");
}

</style>
