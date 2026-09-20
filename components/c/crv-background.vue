<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGZdfpwbKx)" class="m8nr7-gue"/><path fill="url(#SVGyKPPpBtF)" class="h131ktbfo"/><path fill="url(#SVG1KQoSbLV)" class="xp92fcb7r"/><path fill="url(#SVGlzbnsbMH)" class="gz-fhs2xm"/><path fill="url(#SVGyujjNdAO)" class="s6cwk58nl"/><path fill="url(#SVGmcxeGeXn)" class="vg0zhdcto"/><path fill="url(#SVGpGCwcOzp)" class="urm55c0_i"/><path fill="url(#SVGUTRTucbw)" class="r2smjzb2y"/><path fill="url(#SVGnqZXreST)" class="nphozhbwl"/><path fill="url(#SVGl7NXdehI)" class="pmozmlbzy"/><path fill="url(#SVGwcrercqO)" class="ol0kg2b7y"/><path fill="url(#SVG2tbP5bxk)" class="f3rw5tbih"/><path fill="url(#SVG4hSvIcXF)" class="ev-l_vtsh"/><path fill="url(#SVGDUxT3boZ)" class="labyw7t2c"/><path fill="url(#SVGZaGjEcFI)" class="labyw7t2c"/><path fill="url(#SVGtxdb1zNE)" class="nl2a654iv"/><path fill="url(#SVGUBuJrZAH)" class="orsxkzgkp"/><path class="mcfqnv6ir"/></g><defs><linearGradient id="SVGZdfpwbKx" x1="8.986" x2="20.178" y1="4.464" y2="9.603" gradientUnits="userSpaceOnUse"><stop offset=".339" class="nhgbnybxn"/><stop offset=".948" class="xo05v3b5o"/></linearGradient><linearGradient id="SVGyKPPpBtF" x1="5.039" x2="19.781" y1="4.001" y2="14.339" gradientUnits="userSpaceOnUse"><stop class="ymbcisyhw"/><stop offset="1" class="xzjosgb6g"/></linearGradient><linearGradient id="SVG1KQoSbLV" x1="-.872" x2="-1.435" y1="11.236" y2="21.013" gradientUnits="userSpaceOnUse"><stop class="q6oxmbcor"/><stop offset=".314" class="por0vwb0s"/><stop offset=".49" class="f_4b8v52r"/><stop offset=".688" class="ofaosnmdk"/><stop offset="1" class="o2rsw2piw"/></linearGradient><linearGradient id="SVGlzbnsbMH" x1="14.733" x2="19.004" y1="4.499" y2="6.025" gradientUnits="userSpaceOnUse"><stop class="qm6en0b7i"/><stop offset="1" class="pe_ir7b_l"/></linearGradient><linearGradient id="SVGyujjNdAO" x1="15.012" x2="19.891" y1="7.136" y2="7.8" gradientUnits="userSpaceOnUse"><stop class="oob_bt5kk"/><stop offset="1" class="tt26zlqda"/></linearGradient><linearGradient id="SVGmcxeGeXn" x1="5.94" x2="10.079" y1="9.601" y2="23.178" gradientUnits="userSpaceOnUse"><stop class="pfcyh6bhh"/><stop offset="1" class="m6lpkqogp"/></linearGradient><linearGradient id="SVGpGCwcOzp" x1="10.677" x2="13.534" y1="7.606" y2="16.59" gradientUnits="userSpaceOnUse"><stop class="sigu6q_6b"/><stop offset=".469" class="q2vz7-5_m"/><stop offset=".891" class="ofaosnmdk"/><stop offset="1" class="p6ex73b2y"/></linearGradient><linearGradient id="SVGUTRTucbw" x1="12.361" x2="8.55" y1="8.955" y2="17.737" gradientUnits="userSpaceOnUse"><stop class="cyifvkixu"/><stop offset=".469" class="q2vz7-5_m"/><stop offset="1" class="ofaosnmdk"/></linearGradient><linearGradient id="SVGnqZXreST" x1="7.139" x2="20.434" y1="8.062" y2="15.726" gradientUnits="userSpaceOnUse"><stop class="mkybuwbwx"/><stop offset="1" class="cyifvkixu"/></linearGradient><linearGradient id="SVGl7NXdehI" x1="12.003" x2="12.003" y1="3.999" y2="20.002" gradientUnits="userSpaceOnUse"><stop class="jh3o22b4p"/><stop offset="1" class="xzjosgb6g"/></linearGradient><linearGradient id="SVGwcrercqO" x1="9.138" x2="10.398" y1="5.122" y2="20.134" gradientUnits="userSpaceOnUse"><stop class="sf2eu3bbo"/><stop offset=".214" class="m-hpc-68z"/><stop offset=".464" class="ho0yjy8zp"/><stop offset=".688" class="e8rkwzbgp"/><stop offset=".865" class="f3iir7bex"/><stop offset=".974" class="tixjhqbsd"/></linearGradient><linearGradient id="SVG2tbP5bxk" x1="5.88" x2="28.237" y1="11.332" y2="12.037" gradientUnits="userSpaceOnUse"><stop class="txoqg2b0p"/><stop offset="1" class="nn_xi--wp"/></linearGradient><linearGradient id="SVG4hSvIcXF" x1="16.511" x2="15.278" y1="27.63" y2="2.553" gradientUnits="userSpaceOnUse"><stop class="iwsw1wbvv"/><stop offset="1" class="w6p0sac3k"/></linearGradient><linearGradient id="SVGDUxT3boZ" x1="17.402" x2="9.314" y1="9.891" y2="14.322" gradientUnits="userSpaceOnUse"><stop class="m74uv_ccd"/><stop offset="1" class="t7uyutbrm"/></linearGradient><linearGradient id="SVGZaGjEcFI" x1="5.318" x2="12.209" y1="5.701" y2="8.193" gradientUnits="userSpaceOnUse"><stop class="p-wftxb3u"/><stop offset="1" class="oi9ml243e"/></linearGradient><linearGradient id="SVGtxdb1zNE" x1="7.933" x2="8.515" y1="11.37" y2="22.409" gradientUnits="userSpaceOnUse"><stop class="q6oxmbcor"/><stop offset=".314" class="por0vwb0s"/><stop offset=".49" class="f_4b8v52r"/><stop offset=".688" class="ofaosnmdk"/><stop offset="1" class="trtpgbb3m"/></linearGradient><linearGradient id="SVGUBuJrZAH" x1="4.805" x2="11.146" y1="9.695" y2="19.308" gradientUnits="userSpaceOnUse"><stop class="t7dn-obdm"/><stop offset="1" class="pb4k9xbzv"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:crv-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.cyifvkixu {
  stop-color: var(--svg-color--f1fc06, #f1fc06);
}

.e8rkwzbgp {
  stop-color: var(--svg-color--36ffc1, #36ffc1);
}

.ev-l_vtsh {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M7.221 12.847c-.84.155-1.534-.108-1.776-.26c.23-.461.827-1.465 1.958-1.542c1.022-.07 1.676.755 1.97 1.377c-.428-.034-1.312.27-2.152.425");
}

.f_4b8v52r {
  stop-color: var(--svg-color--87ff70, #87ff70);
}

.f3iir7bex {
  stop-color: var(--svg-color--00a0ff, #00a0ff);
}

.f3rw5tbih {
  d: path("M7.221 12.847c-.84.155-1.534-.108-1.776-.26c.23-.461.827-1.465 1.958-1.542c1.022-.07 1.676.755 1.97 1.377c-.428-.034-1.312.27-2.152.425");
}

.ft5dv1b6b {
  fill: none;
}

.gz-fhs2xm {
  d: path("M4.567 7.842c.095-.766.575-1.686.88-2.111L10.9 4.084c5.586.927 4.283 3.194.138 2.803c-1.277-.12-.661 1.067-.586 2.164c.345 2.329-.18 2.6-.992 3.801c-.285-.586-.917-1.697-2.043-1.773c-.902-.06-1.778 1.082-1.969 1.502c-.05-.044-.22-.805-.315-1.117c-.5-1.043-.736-2.25-.565-3.622");
}

.h131ktbfo {
  d: path("M14.812 5.803c-.944-.174-1.006 1.04-.877 1.72c2.516.993 3.358 2.471 3.42 2.565c1.15-.978 2.32.115 2.424.95c-.125-2.71-3.682-4.999-4.967-5.235");
}

.ho0yjy8zp {
  stop-color: var(--svg-color--a4ff53, #a4ff53);
}

.iwsw1wbvv {
  stop-color: var(--svg-color--dffd18, #dffd18);
}

.jh3o22b4p {
  stop-color: var(--svg-color--ffd701, #ffd701);
}

.labyw7t2c {
  d: path("M8.493 20c1.439.032 2.354-1.856 2.632-2.804l-1.362-.106c-.124.551-.752 1.612-1.933 1.747c-1.254.144-2.188-1.433-2.479-2.226a.3.3 0 0 1-.117.066C5.618 17.87 6.694 19.96 8.493 20");
}

.m-hpc-68z {
  stop-color: var(--svg-color--deff19, #deff19);
}

.m6lpkqogp {
  stop-color: var(--svg-color--fa0f01, #fa0f01);
}

.m74uv_ccd {
  stop-color: var(--svg-color--14f3e6, #14f3e6);
}

.m8nr7-gue {
  d: path("M19.556 12.209c-.96 2.48-5.064 3.205-9.166 1.617c-3.867-1.497-7.433-7.61-2.611-9.636c1.712-.384 3.9-.195 6.088.652c4.102 1.587 6.649 4.886 5.69 7.367");
}

.mcfqnv6ir {
  fill: var(--svg-color--f4ba0c, #f4ba0c);
  d: path("M7.48 12.806c-.897.24-1.703-.024-1.993-.186a3.4 3.4 0 0 0-.364 1.155c1.247.374 3.507-.42 4.481-.864l-.226-.484c-.258.026-1 .14-1.897.38");
}

.mkybuwbwx {
  stop-color: var(--svg-color--ffc100, #ffc100);
}

.nhgbnybxn {
  stop-color: var(--svg-color--ff7301, #ff7301);
}

.nl2a654iv {
  d: path("M10.242 8.114c.647 2.087-.167 3.91-.706 4.614c.845 1.966.233 3.905.233 4.456s1.176.405 1.36 0c.679-2.105.64-5.836-.887-9.07");
}

.nn_xi--wp {
  stop-color: var(--svg-color--ffdb00, #ffdb00);
}

.nphozhbwl {
  d: path("M17.365 10.105c-.615-2.314-6.356-3.569-6.944-3.162c-.352.243-.209 1.181 0 1.71c2.845-.279 5.513 1.113 6.411 1.824c.142-.033.48-.29.533-.372");
}

.o2rsw2piw {
  stop-color: var(--svg-color--00beff, #00beff);
}

.ofaosnmdk {
  stop-color: var(--svg-color--1cffdb, #1cffdb);
}

.oi9ml243e {
  stop-color: var(--svg-color--0001fc, #0001fc);
  stop-opacity: 0;
}

.ol0kg2b7y {
  d: path("M7.878 18.87c1.39-.108 2.38-1.937 2.212-4.084c-.169-2.147-1.432-3.8-2.822-3.69s-2.38 1.938-2.212 4.085s1.432 3.799 2.822 3.69");
}

.oob_bt5kk {
  stop-color: var(--svg-color--fa0f00, #fa0f00);
}

.orsxkzgkp {
  d: path("m5.9 12.767l-.433-.176c.12-.374.715-1.485 1.913-1.546c-.379.11-1.315.99-1.48 1.722");
}

.p-wftxb3u {
  stop-color: var(--svg-color--09d3f3, #09d3f3);
}

.p6ex73b2y {
  stop-color: var(--svg-color--00dcfe, #00dcfe);
}

.pb4k9xbzv {
  stop-color: var(--svg-color--f4bb0c, #f4bb0c);
}

.pe_ir7b_l {
  stop-color: var(--svg-color--ff7300, #ff7300);
}

.pfcyh6bhh {
  stop-color: var(--svg-color--a80000, #a80000);
}

.pmozmlbzy {
  d: path("M18.29 10.584c-1.198.228-1.098-.274-.898-.554c.635-.779 1.723-.324 2.187 0c.07.09-.09.327-1.288.554");
}

.por0vwb0s {
  stop-color: var(--svg-color--d4ff23, #d4ff23);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q2vz7-5_m {
  stop-color: var(--svg-color--7aff7d, #7aff7d);
}

.q6oxmbcor {
  stop-color: var(--svg-color--ff9100, #ff9100);
}

.qm6en0b7i {
  stop-color: var(--svg-color--ff4e00, #ff4e00);
}

.r2smjzb2y {
  d: path("M10.502 8.638c-.25.106.571 2.159.837 3.185c4.129-.309 5.504-1.333 5.521-1.333c-2.315-1.918-6.044-1.985-6.358-1.852");
}

.s6cwk58nl {
  d: path("M5.173 7.798c-.157-.679-.066-1.285 0-1.503c.156-.596.938-1.86 2.814-2.156c1.876-.295 3.555-.046 4.16.281c.575.387.327 1.56-.842 1.23c-1.703-.492-1.966.157-1.826 1.053c.38 1.98.158 3.306 0 3.721c0 0-.51 1.282-.93.879c-.72-.72-1.387-.58-2.125-.387c-.59.154-.767-.263-.782-.492c-.091-.592-.312-1.947-.47-2.626");
}

.sf2eu3bbo {
  stop-color: var(--svg-color--ffa300, #ffa300);
}

.sigu6q_6b {
  stop-color: var(--svg-color--ffe600, #ffe600);
}

.t7dn-obdm {
  stop-color: var(--svg-color--ff4e01, #ff4e01);
}

.t7uyutbrm {
  stop-color: var(--svg-color--0040ff, #0040ff);
}

.tixjhqbsd {
  stop-color: var(--svg-color--0064ff, #0064ff);
}

.trtpgbb3m {
  stop-color: var(--svg-color--00d8ff, #00d8ff);
}

.tt26zlqda {
  stop-color: var(--svg-color--ff6e01, #ff6e01);
}

.txoqg2b0p {
  stop-color: var(--svg-color--ff8a01, #ff8a01);
}

.urm55c0_i {
  d: path("M17.418 10.036c-1.058 1.18-4.514 1.663-6.11 1.757c.333 1.595.03 4.025-.162 5.04c2.057-.65 6.336-1.983 7-2.119c.831-.17 1.848-1.475 1.679-3.373s-1.729-2.017-2.407-1.305");
}

.vg0zhdcto {
  d: path("M6.822 4.49c-1.338.637-.854 3.128-.437 4.36c.454-.285 1.846-.172 2.273.283c-.637-3.614.868-5.06 1.322-5.032c0 0-.747-.08-1.266-.036c-.624.035-1.295.14-1.892.425");
}

.w6p0sac3k {
  stop-color: var(--svg-color--fdad12, #fdad12);
}

.xo05v3b5o {
  stop-color: var(--svg-color--ffdd01, #ffdd01);
}

.xp92fcb7r {
  d: path("M5.35 16.618c-.66-2.03-.055-3.818.33-4.458c-.345-1.602-.994-4.819-1.014-4.799c-1.139 4.006-.11 7.89.571 9.322z");
}

.xzjosgb6g {
  stop-color: var(--svg-color--ffe601, #ffe601);
}

.ymbcisyhw {
  stop-color: var(--svg-color--ff8101, #ff8101);
}

</style>
