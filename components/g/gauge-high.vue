<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tcta15-ti"/><path class="g2kx7ng5b"/><path class="m6d8fab6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gauge-high" /></template>
<style>
.g2kx7ng5b {
  fill: currentColor;
  d: path("M12 12h.01");
}

.m6d8fab6w {
  d: path("m12 12l4.5-4.5M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

.tcta15-ti {
  d: path("M17.086 12H3q0-.221.011-.442q.011-.22.033-.44q.021-.22.054-.438q.032-.219.075-.435q.044-.217.097-.431q.054-.215.118-.426t.139-.419q.074-.208.159-.412t.179-.404t.199-.394q.104-.195.217-.385q.114-.189.237-.373q.123-.183.254-.361q.132-.177.272-.348t.289-.334q.148-.164.304-.32t.32-.304q.164-.149.335-.289q.17-.14.348-.272q.177-.131.361-.254q.184-.122.373-.236t.384-.218t.395-.198t.404-.179t.412-.159t.419-.139t.426-.117q.214-.054.431-.097q.216-.043.435-.076q.218-.032.438-.054t.44-.032q.221-.011.442-.011t.442.011t.44.032q.22.022.438.054q.219.033.435.076q.217.043.431.097q.215.053.426.117q.211.065.419.139t.412.159t.404.179t.395.198t.384.218t.373.236q.184.123.361.254q.178.132.348.272q.171.14.335.289t.32.304t.304.32q.149.163.289.334t.272.348t.254.361t.237.373q.113.19.217.385q.104.194.199.394q.094.2.179.404t.159.412t.139.419t.118.426t.097.431t.075.435q.033.218.054.438q.022.22.033.44q.011.221.011.442h-2.014");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
