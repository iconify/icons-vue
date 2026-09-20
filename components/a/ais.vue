<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG0tWcMdbB)" class="d5nlp7-ny"/><path fill="url(#SVGLf9Rbcul)" class="gd-c57c7a"/><path class="a4ob4bj2z"/><path class="tcg1i1b-f"/><path class="l28m8jb4s"/><path class="guye1hbce"/><path class="cefv2ksok"/><path fill="url(#SVGl7XvwcGz)" class="fh_cuhk7v"/><path fill="url(#SVGLNNkrdbe)" class="jxx5pm1ml"/><path class="mpw67zb9u"/><path fill="url(#SVGdSqHWdPc)" class="rxgde6-dd"/><path class="xy5feo22l"/><path class="x19cevx7t"/><path fill="url(#SVGNQtuRbgc)" class="w16mkmbon"/><path class="vrolgpipx"/><path fill="url(#SVG0dPb5drq)" class="li_bg3b6v"/><path class="pb-ut5b3f"/><path class="n50t0gb3l"/><path fill="url(#SVGFfz89bdU)" class="jaf5iibid"/><path class="m1v11x5wr"/><path fill="url(#SVG7G9DydXk)" class="t8r16acgg"/><path fill="url(#SVGkUwNQOve)" class="zisdvt4lz"/><path class="a68iq6b0f"/><path fill="url(#SVGVWasHkGY)" class="sj--bbcan"/><path fill="url(#SVGAVuEQe8H)" class="s09i13btu"/><path fill="url(#SVGb6bZDd2p)" class="f8m4yq-1c"/><path class="rx-j70b6l"/><path class="lu83ghbkw"/><path fill="url(#SVGe1X90bgy)" class="fb8bc1ehj"/><path class="yks45brps"/><path class="kd8hp2k4u"/><path fill="url(#SVGQt5ZRdVG)" class="k2bet4bzf"/><path class="npgyblbmo"/><path class="spcqkgbmi"/><path fill="url(#SVG74JepdIB)" class="g5y_tub1h"/><defs><linearGradient id="SVG0tWcMdbB" x1="16.728" x2="8.638" y1="11.864" y2="18.144" gradientUnits="userSpaceOnUse"><stop class="mzvkjibil"/><stop offset=".89" class="g__t-db2o"/><stop offset="1" class="n6e5qnizr"/></linearGradient><linearGradient id="SVGLf9Rbcul" x1="9.202" x2="15.959" y1="11.98" y2="11.98" gradientUnits="userSpaceOnUse"><stop class="eot9-iboe"/><stop offset="1" class="zqe3sfp-o"/></linearGradient><linearGradient id="SVGl7XvwcGz" x1="10.867" x2="15.425" y1="12.082" y2="11.615" gradientUnits="userSpaceOnUse"><stop class="i3mjz2_ek"/><stop offset="1" class="lqtad391h"/></linearGradient><linearGradient id="SVGLNNkrdbe" x1="12.038" x2="12.038" y1="3" y2="11.09" gradientUnits="userSpaceOnUse"><stop class="xu26p64eq"/><stop offset=".84" class="pefctsiyw"/><stop offset=".98" class="bk9x7iqge"/></linearGradient><linearGradient id="SVGdSqHWdPc" x1="11.955" x2="11.955" y1="5.078" y2="10.551" gradientUnits="userSpaceOnUse"><stop class="ooh_9k4ad"/><stop offset="1" class="kmjnxhbim"/></linearGradient><linearGradient id="SVGNQtuRbgc" x1="5.826" x2="5.826" y1="3.248" y2="8.823" gradientUnits="userSpaceOnUse"><stop class="xu26p64eq"/><stop offset="1" class="y_om08fzx"/></linearGradient><linearGradient id="SVG0dPb5drq" x1="5.383" x2="5.383" y1="6.522" y2="8.128" gradientUnits="userSpaceOnUse"><stop class="ey368abkl"/><stop offset="1" class="asgqqo9zr"/></linearGradient><linearGradient id="SVGFfz89bdU" x1="18.172" x2="18.172" y1="3.248" y2="8.823" gradientUnits="userSpaceOnUse"><stop class="xu26p64eq"/><stop offset="1" class="y_om08fzx"/></linearGradient><linearGradient id="SVG7G9DydXk" x1="18.621" x2="18.621" y1="6.522" y2="8.128" gradientUnits="userSpaceOnUse"><stop class="ey368abkl"/><stop offset="1" class="asgqqo9zr"/></linearGradient><linearGradient id="SVGkUwNQOve" x1="8.03" x2="15.741" y1="6.892" y2="6.892" gradientUnits="userSpaceOnUse"><stop class="b3b5x9hgv"/><stop offset=".61" class="gp9o56bzr"/><stop offset="1" class="c05z9abfq"/></linearGradient><linearGradient id="SVGVWasHkGY" x1="9.694" x2="9.543" y1="5.777" y2="7.329" gradientUnits="userSpaceOnUse"><stop class="w2_a9w03v"/><stop offset="1" class="su-qurb2l"/></linearGradient><linearGradient id="SVGAVuEQe8H" x1="10.347" x2="10.347" y1="6.254" y2="8.472" gradientUnits="userSpaceOnUse"><stop class="tcwfh8r2x"/><stop offset="1" class="fs7qicbfv"/></linearGradient><linearGradient id="SVGb6bZDd2p" x1="13.863" x2="13.863" y1="6.254" y2="8.472" gradientUnits="userSpaceOnUse"><stop class="tcwfh8r2x"/><stop offset="1" class="fs7qicbfv"/></linearGradient><linearGradient id="SVGe1X90bgy" x1="6.434" x2="6.434" y1="11.694" y2="18.772" gradientUnits="userSpaceOnUse"><stop class="k62h8_bnf"/><stop offset="1" class="ukk4ckuxn"/></linearGradient><linearGradient id="SVGQt5ZRdVG" x1="17.458" x2="17.458" y1="11.694" y2="18.772" gradientUnits="userSpaceOnUse"><stop class="k62h8_bnf"/><stop offset="1" class="ukk4ckuxn"/></linearGradient><linearGradient id="SVG74JepdIB" x1="9.917" x2="14.315" y1="14.783" y2="14.783" gradientUnits="userSpaceOnUse"><stop class="sz1ookb5h"/><stop offset="1" class="y67b_kfcx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ais" /></template>
<style>
.a4ob4bj2z {
  fill: var(--svg-color--26203a, #26203a);
  d: path("M12.142 11.888c-2.462 0-3.007-.594-2.973-.896h5.935v.112c.04.258-.5.784-2.962.784");
}

.a68iq6b0f {
  fill: var(--svg-color--483d6f, #483d6f);
  d: path("M15.498 8.63a8 8 0 0 1-3.415.671c-1.606 0-2.788-.257-3.513-.481c.628.939 1.776 1.63 3.367 1.63c1.741 0 2.972-.73 3.56-1.82");
}

.asgqqo9zr {
  stop-color: var(--svg-color--5ea3e0, #5ea3e0);
}

.b3b5x9hgv {
  stop-color: var(--svg-color--27213b, #27213b);
}

.bk9x7iqge {
  stop-color: var(--svg-color--4a6dd8, #4a6dd8);
}

.c05z9abfq {
  stop-color: var(--svg-color--28223c, #28223c);
}

.cefv2ksok {
  fill: var(--svg-color--9ea3b6, #9ea3b6);
  d: path("m9.227 11.046l-.623-.117c.015.365.584 1.066 2.71.94c-1.591-.074-2.053-.58-2.092-.828z");
}

.d5nlp7-ny {
  d: path("M7.49 15.532c-.098-1.07-.18-3.42-.21-4.456c.059-.238.39-.409.54-.467c2.238-.015 6.913-.049 7.75-.049c.832 0 1.119.472 1.158.715c-.059.36-.175 1.547-.175 3.425c0 2.345-2.248 6.3-4.52 6.3s-4.417-4.13-4.544-5.468");
}

.eot9-iboe {
  stop-color: var(--svg-color--6192e0, #6192e0);
}

.ey368abkl {
  stop-color: var(--svg-color--32469f, #32469f);
}

.f8m4yq-1c {
  d: path("M13.863 8.472c.583 0 1.056-.497 1.056-1.11c0-.612-.473-1.108-1.056-1.108s-1.055.496-1.055 1.109c0 .612.472 1.109 1.055 1.109");
}

.fb8bc1ehj {
  d: path("M5.257 16.038c0 2.029.652 2.666.973 2.734c.929 0 1.265-2.282 1.313-3.42c.112-1.221.166-3.658-.496-3.658c-.827 0-1.79 1.814-1.79 4.344");
}

.fh_cuhk7v {
  d: path("M11.232 11.868h-.837c3.298.481 5.492-.302 5.167-.925l-.56.098c.005.778-2.51.875-3.77.827");
}

.fs7qicbfv {
  stop-color: var(--svg-color--fcbe43, #fcbe43);
}

.ft5dv1b6b {
  fill: none;
}

.g__t-db2o {
  stop-color: var(--svg-color--1b5ccf, #1b5ccf);
}

.g5y_tub1h {
  d: path("M10.277 13.445L9.61 15.09H10l.661-1.57a.1.1 0 0 1 .088-.054a.1.1 0 0 1 .087.053l.623 1.571h.399l-.647-1.639a.5.5 0 0 0-.467-.311a.5.5 0 0 0-.467.306m1.844-.306h.399v1.95h-.4v-1.95m.807 1.96v-.365h1.168c.136 0 .248-.107.248-.233a.24.24 0 0 0-.243-.229h-.633c-.321 0-.584-.248-.584-.554s.263-.555.584-.555h1.066v.345h-1.046c-.132 0-.244.103-.244.23c0 .12.112.223.244.223h.598c.336 0 .603.258.603.57a.583.583 0 0 1-.603.568z");
}

.gd-c57c7a {
  d: path("M10.214 11.84q-1.15-.06-2.287-.244c.419.238 1.849.705 4.233.705c2.982 0 4.208-.574 4.208-.924c0-.287-.278-.452-.419-.506l-.384.083c.03.042.045.094.044.146c-.4.812-2.306.924-3.454.924c-.91 0-1.674-.122-1.946-.185z");
}

.gp9o56bzr {
  stop-color: var(--svg-color--4a3f73, #4a3f73);
}

.guye1hbce {
  fill: var(--svg-color--496bac, #496bac);
  d: path("M7.68 11.237c0 .184.189.33.281.379c.487.083 1.625.248 2.287.238c-1.265-.18-1.606-.69-1.61-.924l-.628-.097c-.107.053-.33.219-.33.403");
}

.i3mjz2_ek {
  stop-color: var(--svg-color--b9c5de, #b9c5de);
}

.jaf5iibid {
  d: path("M18.81 6.386c0 1.814-.56 2.383-.837 2.437c-.56 0-.448-.959-.37-2.773c.073-1.815.306-2.802.462-2.802s.744.87.744 3.138");
}

.jxx5pm1ml {
  d: path("M14.646 11.09H9.601c-.53 0-1.8-.156-2.627-.768c-1.046-.774-.72-2.788-.603-3.221C6.488 6.673 7.568 3 11.985 3c4.422 0 5.79 3.99 5.838 4.592v.02a4 4 0 0 1-.37 2.233c-.37.827-2 1.182-2.807 1.245");
}

.k2bet4bzf {
  d: path("M18.635 16.038c0 2.029-.647 2.666-.973 2.734c-.924 0-1.265-2.282-1.314-3.42c-.107-1.221-.16-3.658.501-3.658c.828 0 1.786 1.814 1.786 4.344");
}

.k62h8_bnf {
  stop-color: var(--svg-color--87b7fd, #87b7fd);
}

.kd8hp2k4u {
  fill: var(--svg-color--ffffba, #ffffba);
  d: path("M6.337 16.635c-.643 0-.993.049-1.12.073l-.029-.146c.137-.024.497-.073 1.149-.073c.564 0 .875.078 1.06.122l.088.024l-.04.146l-.087-.024a3.7 3.7 0 0 0-1.021-.122");
}

.kmjnxhbim {
  stop-color: var(--svg-color--d2dbed, #d2dbed);
}

.l28m8jb4s {
  fill: var(--svg-color--335ca7, #335ca7);
  d: path("M7.295 11.173c0-.17.257-.394.389-.486l.38.146l-.161.749a4 4 0 0 1-.589-.18a.8.8 0 0 1-.02-.224z");
}

.li_bg3b6v {
  d: path("M5.446 8.128c.063-.175.126-.423.126-.73c0-.433-.228-.74-.38-.876c.01.73.118 1.25.254 1.606");
}

.lqtad391h {
  stop-color: var(--svg-color--667ab0, #667ab0);
}

.lu83ghbkw {
  fill: var(--svg-color--28233e, #28233e);
  d: path("M7.281 11.68v.112c-.048.564-.156 1.722-.156 1.814s.22.691.331.983c.068-.19.205-.745.205-1.44c0-.696-.253-1.265-.38-1.47");
}

.m1v11x5wr {
  fill: var(--svg-color--ffffba, #ffffba);
  d: path("M17.847 4.728c.496.082.851 0 .89 0c.059.014.034.078.015.112q-.202.046-.409.039c-.287 0-.467-.02-.496-.04c-.024-.019-.01-.082 0-.111");
}

.mpw67zb9u {
  fill: var(--svg-color--ffffba, #ffffba);
  d: path("M13.746 4.99h-3.352c-.837 0-2.72.195-2.72 2.01s1.538 3.648 4.257 3.648c2.72 0 4.301-1.62 4.301-3.649c0-1.625-1.654-2.019-2.486-2.009");
}

.mzvkjibil {
  stop-color: var(--svg-color--89b9ed, #89b9ed);
}

.n50t0gb3l {
  fill: var(--svg-color--251f38, #251f38);
  d: path("M17.312 6.697c.092.014.243.438.301.642c.04.204.112.71.098 1.07c-.005.36-.068.477-.098.487c-.17 0-.301-.487-.34-.842c-.039-.35-.073-1.372.039-1.357");
}

.n6e5qnizr {
  stop-color: var(--svg-color--6095d0, #6095d0);
}

.npgyblbmo {
  fill: var(--svg-color--829fd1, #829fd1);
  d: path("M18.456 16.413c0 .71-.2.895-.302.9c-.238 0-.233-.633-.204-.949c0-.467.034-1.4.204-1.4c.22 0 .302.563.302 1.449");
}

.ooh_9k4ad {
  stop-color: var(--svg-color--8091bf, #8091bf);
}

.pb-ut5b3f {
  fill: var(--svg-color--c9d3e8, #c9d3e8);
  d: path("M17.321 6.474c.107.014.277.52.35.768c.049.253.127.861.117 1.294c-.015.438-.083.574-.117.584c-.194 0-.35-.584-.389-1.012c-.049-.423-.087-1.654.039-1.634");
}

.pefctsiyw {
  stop-color: var(--svg-color--3856dc, #3856dc);
}

.rx-j70b6l {
  fill: var(--svg-color--ffffba, #ffffba);
  d: path("M8.891 5.35c-.243-.291-.535-.836-.662-1.109l.18-.14c.02.184.41.865.609 1.181c-.03.025-.093.069-.127.069m6.115-.019a5.4 5.4 0 0 0 .764-1.036l-.195-.146c-.034.18-.462.803-.7 1.104a.4.4 0 0 0 .131.078");
}

.rxgde6-dd {
  d: path("M13.687 5.083h-3.245c-.812 0-2.632.185-2.632 1.946c0 1.751 1.489 3.522 4.116 3.522c2.632 0 4.164-1.557 4.164-3.527c0-1.572-1.605-1.946-2.408-1.946z");
}

.s09i13btu {
  d: path("M10.347 8.472c.583 0 1.055-.497 1.055-1.11c0-.612-.472-1.108-1.055-1.108S9.29 6.75 9.29 7.363c0 .612.473 1.109 1.056 1.109");
}

.sj--bbcan {
  d: path("M9.558 6.614h-.827a1.05 1.05 0 0 1 1.046-.837zm1.216-.832h-.91l-.19.818h1.1zm-2.072.925h.837l-.078.34h-.847z");
}

.spcqkgbmi {
  fill: var(--svg-color--ffffba, #ffffba);
  d: path("M17.554 16.635c.648 0 .998.049 1.12.073l.033-.146c-.136-.024-.5-.073-1.153-.073c-.564 0-.87.078-1.06.122l-.083.024l.034.146l.088-.024c.194-.049.476-.122 1.021-.122");
}

.su-qurb2l {
  stop-color: var(--svg-color--9490a1, #9490a1);
  stop-opacity: 0;
}

.sz1ookb5h {
  stop-color: var(--svg-color--c6ad40, #c6ad40);
}

.t8r16acgg {
  d: path("M18.553 8.128a2.1 2.1 0 0 1-.122-.73c0-.433.229-.74.38-.876a4.7 4.7 0 0 1-.258 1.606");
}

.tcg1i1b-f {
  fill: var(--svg-color--4470d1, #4470d1);
  d: path("M12.14 11.582c-1.615 0-1.975-.39-1.946-.584h3.887v.068c.025.17-.33.516-1.945.516z");
}

.tcwfh8r2x {
  stop-color: var(--svg-color--fff962, #fff962);
}

.ukk4ckuxn {
  stop-color: var(--svg-color--325ca9, #325ca9);
}

.vrolgpipx {
  fill: var(--svg-color--ffffba, #ffffba);
  d: path("M6.158 4.728c-.496.082-.851 0-.89 0c-.059.014-.034.078-.02.112c.049.014.185.039.414.039c.287 0 .467-.02.496-.04c.02-.019.01-.082 0-.111");
}

.w16mkmbon {
  d: path("M5.188 6.386c0 1.814.56 2.383.842 2.437c.56 0 .443-.959.37-2.773s-.307-2.802-.462-2.802s-.745.87-.745 3.138z");
}

.w2_a9w03v {
  stop-color: var(--svg-color--9490a1, #9490a1);
}

.x19cevx7t {
  fill: var(--svg-color--251f38, #251f38);
  d: path("M6.692 6.697c-.093.014-.243.438-.307.642c-.034.204-.107.71-.097 1.07s.068.477.097.487c.175 0 .307-.487.34-.842c.045-.35.079-1.372-.033-1.357");
}

.xu26p64eq {
  stop-color: var(--svg-color--72cdff, #72cdff);
}

.xy5feo22l {
  fill: var(--svg-color--c9d3e8, #c9d3e8);
  d: path("M6.678 6.474c-.102.014-.273.52-.346.768a7.5 7.5 0 0 0-.116 1.294c.01.438.082.574.116.584c.195 0 .346-.584.39-1.012c.048-.423.087-1.654-.044-1.634");
}

.y_om08fzx {
  stop-color: var(--svg-color--252b8c, #252b8c);
}

.y67b_kfcx {
  stop-color: var(--svg-color--ffe45b, #ffe45b);
}

.yks45brps {
  fill: var(--svg-color--829fd1, #829fd1);
  d: path("M5.441 16.413c0 .71.195.895.297.9c.243 0 .239-.633.204-.949c.005-.467-.029-1.4-.204-1.4c-.214 0-.297.563-.297 1.449");
}

.zisdvt4lz {
  d: path("M13.595 5.185h-3.07c-.768 0-2.495.18-2.495 1.868c0 1.693 1.41 3.395 3.906 3.395c2.49 0 3.946-1.503 3.946-3.395c0-1.508-1.523-1.873-2.287-1.868");
}

.zqe3sfp-o {
  stop-color: var(--svg-color--97c1ef, #97c1ef);
}

</style>
