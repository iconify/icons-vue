<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="y-jqxs3dx"/><circle class="grh6rreot"/><circle class="tqi-pczqx"/><path class="udw47wb3u"/><path class="tc9cx4bhc"/><path class="btxun9sfv"/><circle class="qt_xlwb4i"/><circle class="tk4v4hbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:compass" /></template>
<style>
.btxun9sfv {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M18.657 15.267L9.879 9.886l5.38 8.779z");
}

.grh6rreot {
  cx: 18px;
  cy: 18px;
  r: 14.5px;
  fill: var(--svg-color--ffd983, #ffd983);
}

.qt_xlwb4i {
  cx: 18px;
  cy: 18.008px;
  r: 3.055px;
  fill: var(--svg-color--8899a6, #8899a6);
}

.tc9cx4bhc {
  fill: var(--svg-color--292f33, #292f33);
  d: path("m17.343 20.748l8.777 5.381l-5.379-8.778z");
}

.tk4v4hbqx {
  cx: 18px;
  cy: 18.008px;
  r: 1.648px;
  fill: var(--svg-color--f5f8fa, #f5f8fa);
}

.tqi-pczqx {
  cx: 18px;
  cy: 18px;
  r: 13px;
  fill: var(--svg-color--f5f8fa, #f5f8fa);
}

.udw47wb3u {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("m18 8l1.531 6.304l5.54-3.375l-3.375 5.54L28 18l-6.304 1.531l3.375 5.54l-5.54-3.375L18 28l-1.531-6.304l-5.54 3.375l3.375-5.54L8 18l6.304-1.531l-3.375-5.54l5.54 3.375z");
}

.y-jqxs3dx {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--f4900c, #f4900c);
}

</style>
