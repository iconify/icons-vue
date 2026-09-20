<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVG55q3SAcG" x1="-12.564%" x2="101.304%" y1="108.214%" y2="-1.964%"><stop offset="0%" class="cn4ynabaa"/><stop offset="10.996%" class="k2vs_lbar"/><stop offset="94.502%" class="ebbg0xbtb"/></linearGradient><linearGradient id="SVGOOYVAbzB" x1="-12.564%" x2="101.304%" y1="108.214%" y2="-1.964%"><stop offset="0%" class="cn4ynabaa"/><stop offset="8.048%" class="k2vs_lbar"/><stop offset="41.874%" class="ebbg0xbtb"/></linearGradient><linearGradient id="SVG3AVM5ouD" x1="74.724%" x2="6.653%" y1="-3.059%" y2="100.066%"><stop offset="0%" class="x9e2iddey"/><stop offset="41.191%" class="k2vs_lbar"/><stop offset="73.271%" class="ebbg0xbtb"/></linearGradient><circle id="SVGN5eQqeMK" class="ugn0xccey"/></defs><mask id="SVGMX2wGdvm" class="n1mjunbsu"><use href="#SVGN5eQqeMK"/></mask><circle fill="url(#SVG55q3SAcG)" mask="url(#SVGMX2wGdvm)" class="hj_2n5_ab"/><path fill="url(#SVGOOYVAbzB)" mask="url(#SVGMX2wGdvm)" class="sxrg05h1v"/><path fill="url(#SVG3AVM5ouD)" mask="url(#SVGMX2wGdvm)" class="n8epy8cmi"/><path mask="url(#SVGMX2wGdvm)" class="jdh1_pbjq"/><path mask="url(#SVGMX2wGdvm)" class="hzw4ycc1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:apache-camel" /></template>
<style>
.cn4ynabaa {
  stop-color: var(--svg-color--f69923, #f69923);
}

.ebbg0xbtb {
  stop-color: var(--svg-color--e97826, #e97826);
}

.hj_2n5_ab {
  cx: 127.994px;
  cy: 127.994px;
  r: 123.111px;
}

.hzw4ycc1a {
  fill: var(--svg-color--fff, #fff);
  d: path("M128.747 54.005c-10.985 5.495 0 27.466 0 27.466C95.774 108.954 102.78 155.9 64.312 155.9c-20.97 0-42.242-24.077-64.233-38.828c-.283 3.479-.785 6.972-.785 10.524c0 48.095 26.263 89.924 65.42 111.897c10.952-1.38 22.838-4.114 31.05-9.592c43.146-28.765 53.857-83.491 71.487-109.925c10.979-16.492 62.434-15.061 65.906-22.01c5.502-10.991-10.99-27.467-16.491-27.467h-43.958c-3.071 0-7.897-5.456-10.974-5.456h-16.492s-7.307-11.085-13.794-11.526c-.93-.066-1.83.053-2.7.488");
}

.jdh1_pbjq {
  fill: var(--svg-color--28170b, #28170b);
  d: path("M84.752 77.368C66.895 83.378 32.83 104.546.079 132.81c2.487 67.334 57.028 121.313 124.548 123.07c33.233-64.016 13.901-137.68-39.875-178.513");
  opacity: var(--svg-opacity--0-75, 0.75);
}

.k2vs_lbar {
  stop-color: var(--svg-color--f79a23, #f79a23);
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.n8epy8cmi {
  d: path("M98.044 75.517c-1.751-.002-3.524.01-5.292.061c-2.056.06-4.817.713-8 1.785c53.775 40.834 73.108 114.497 39.875 178.514c1.129.03 2.249.123 3.385.123c60.736 0 111.492-42.323 124.609-99.071c-38.542-45.178-90.813-81.314-154.578-81.412");
  opacity: var(--svg-opacity--0-75, 0.75);
}

.sxrg05h1v {
  d: path("M128 256C57.308 256 0 198.692 0 128S57.308 0 128 0s128 57.308 128 128s-57.308 128-128 128m0-9.768c65.298 0 118.232-52.934 118.232-118.232S193.298 9.768 128 9.768S9.768 62.702 9.768 128S62.702 246.232 128 246.232");
}

.ugn0xccey {
  cx: 128px;
  cy: 128px;
  r: 128px;
}

.x9e2iddey {
  stop-color: var(--svg-color--f6e423, #f6e423);
}

</style>
