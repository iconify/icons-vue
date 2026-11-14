<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x15zqnbwh"/><path class="bh9aw6bfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:firework-rocket" /></template>
<style>
.bh9aw6bfl {
  d: path("m8.957 8.127l-2.496.166a1.5 1.5 0 0 0-.961.436l-.662.662a.772.772 0 0 0 .419 1.308l2.001.333a1.5 1.5 0 0 0 1.308-.419l1.045-1.045a.845.845 0 0 0-.654-1.441m7.045 7.045l-.166 2.496a1.5 1.5 0 0 1-.436.961l-.663.662a.772.772 0 0 1-1.307-.419l-.333-2.002a1.5 1.5 0 0 1 .419-1.307l1.045-1.045a.845.845 0 0 1 1.441.654m-7.275.23l-3.182 3.182");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x15zqnbwh {
  d: path("m20.022 5.845l-.606 3.434a1.5 1.5 0 0 1-.417.8l-4.615 4.616a1.5 1.5 0 0 1-2.121 0l-2.829-2.829a1.5 1.5 0 0 1 0-2.121l4.616-4.616a1.5 1.5 0 0 1 .8-.416l3.434-.606a1.5 1.5 0 0 1 1.738 1.738");
}

</style>
