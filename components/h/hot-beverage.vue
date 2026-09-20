<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<ellipse class="q9zzjubmk"/><ellipse class="myny3pcxb"/><path class="qrlgewicq"/><path class="yerfdxbmu"/><ellipse class="cuzyql1vx"/><path class="iyum1w14c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:hot-beverage" /></template>
<style>
.cuzyql1vx {
  cx: 18px;
  cy: 13px;
  fill: var(--svg-color--8a4b38, #8a4b38);
  rx: 15px;
  ry: 7px;
}

.iyum1w14c {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M20 17a1 1 0 0 1-.707-.293c-2.337-2.337-2.376-4.885-.125-8.262c.739-1.109.9-2.246.478-3.377c-.461-1.236-1.438-1.996-1.731-2.077c-.553 0-.958-.443-.958-.996S17.448 1 18 1c.997 0 2.395 1.153 3.183 2.625c1.034 1.933.91 4.039-.351 5.929c-1.961 2.942-1.531 4.332-.125 5.738A.999.999 0 0 1 20 17m-6-2a1 1 0 0 1-.707-.293c-2.337-2.337-2.376-4.885-.125-8.262c.727-1.091.893-2.083.494-2.947c-.444-.961-1.431-1.469-1.684-1.499a.99.99 0 0 1-.989-1c0-.552.458-1 1.011-1c.997 0 2.585.974 3.36 2.423c.481.899 1.052 2.761-.528 5.131c-1.961 2.942-1.531 4.332-.125 5.738a1 1 0 0 1 0 1.414A1 1 0 0 1 14 15");
}

.myny3pcxb {
  cx: 18px;
  cy: 24px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  rx: 18px;
  ry: 10px;
}

.q9zzjubmk {
  cx: 18px;
  cy: 26px;
  fill: var(--svg-color--99aab5, #99aab5);
  rx: 18px;
  ry: 10px;
}

.qrlgewicq {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M18 31C3.042 31 1 16 1 12h34c0 2-1.958 19-17 19");
}

.yerfdxbmu {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M34.385 9.644c2.442-10.123-9.781-7.706-12.204-5.799A38 38 0 0 0 18 3.611c-9.389 0-17 3.229-17 8.444S8.611 21.5 18 21.5s17-4.229 17-9.444c0-.863-.226-1.664-.615-2.412m-2.503-2.692c-1.357-.938-3.102-1.694-5.121-2.25c1.875-.576 4.551-.309 5.121 2.25");
}

</style>
