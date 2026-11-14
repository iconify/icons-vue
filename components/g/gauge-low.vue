<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eovf0bbcl"/><path class="tfd2rkbmf"/><path class="wemj4d2-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gauge-low" /></template>
<style>
.eovf0bbcl {
  d: path("M3 14q0-.221.011-.442q.011-.22.033-.44q.021-.22.054-.438q.032-.219.075-.435q.044-.217.097-.431q.054-.215.118-.426t.139-.419q.074-.208.159-.412t.179-.404t.199-.394q.104-.195.217-.385q.114-.189.237-.373q.123-.183.254-.361q.132-.177.272-.348t.289-.334q.148-.164.304-.32t.32-.304q.164-.149.335-.289q.17-.14.348-.272q.177-.131.361-.254q.184-.122.373-.236t.384-.218t.395-.198t.404-.179t.412-.159t.419-.139q.211-.064.426-.117q.214-.054.431-.097q.216-.043.435-.076q.218-.032.438-.054t.44-.032q.221-.011.442-.011q.368 0 .735.03t.73.09t.72.149q.358.09.706.208q.349.118.687.265q.337.146.662.319t.634.373t.602.424t.565.471t.525.515q.251.269.48.557t.434.594t.384.628t.331.657t.277.681q.124.347.219.702m.075.299Q21 12.969 21 14");
}

.tfd2rkbmf {
  fill: currentColor;
  d: path("M10.75 14a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wemj4d2-s {
  d: path("m12 14l-5.25-3M18 14.5v7m-3-3l3 3l3-3");
}

</style>
