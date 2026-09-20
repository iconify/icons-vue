<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><circle id="SVGN5eQqeMK" class="ugn0xccey"/></defs><mask id="SVGMX2wGdvm" class="n1mjunbsu"><use href="#SVGN5eQqeMK"/></mask><use href="#SVGN5eQqeMK" class="zc67_2h3s"/><path mask="url(#SVGMX2wGdvm)" class="sedkwobvu"/><path class="cu_ubl15l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:designernews" /></template>
<style>
.cu_ubl15l {
  fill: var(--svg-color--fff, #fff);
  d: path("M118.837 131.159c0-27.131-16.675-45.528-48.439-45.528H39.032v91.32H71.06c30.837 0 47.777-18.66 47.777-45.792m-22.763.132c0 19.588-10.059 28.058-26.205 28.058h-8.206v-56.115h8.206c15.484 0 26.205 8.867 26.205 28.057m112.892 45.66v-91.32h-21.043v51.087L154.307 85.63h-21.97v91.32h21.043v-54.66l35.999 54.66z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.sedkwobvu {
  fill: var(--svg-color--666c76, #666c76);
  d: path("m38.715 176.727l107.34 79.844l264.006 16.604L207.754 85.924v42.688l-18.874-13.517l-35.122-29.171l-20.908 34.083l-29.395-24.54L51.77 92.19z");
}

.ugn0xccey {
  cx: 128px;
  cy: 128px;
  r: 128px;
}

.zc67_2h3s {
  fill: var(--svg-color--b3bbc6, #b3bbc6);
}

</style>
