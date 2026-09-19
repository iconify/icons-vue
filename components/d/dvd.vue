<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="iqhz24bmv"/><circle class="hk0e3zb2y"/><path class="qitu79e0r"/><path class="ogwjdbchm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:dvd" /></template>
<style>
.hk0e3zb2y {
  cx: 32px;
  cy: 32px;
  r: 6.6px;
  fill: var(--svg-color--fff, #fff);
}

.iqhz24bmv {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--c28fef, #c28fef);
}

.ogwjdbchm {
  fill: var(--svg-color--9450e0, #9450e0);
  d: path("M32 45c-7.1 0-13-5.8-13-13c0-7.1 5.8-13 13-13s13 5.8 13 13c0 7.1-5.9 13-13 13m0-23.3c-5.7 0-10.3 4.6-10.3 10.3S26.3 42.3 32 42.3S42.3 37.7 42.3 32S37.7 21.7 32 21.7");
}

.qitu79e0r {
  fill: var(--svg-color--ffc7ce, #ffc7ce);
  d: path("m32.2 42.6l9.2 13.6c6.8-2.6 12.2-8 14.8-14.8l-13.6-9.2c-.1 5.7-4.7 10.3-10.4 10.4m-.4-21.2L22.6 7.8c-6.8 2.6-12.2 8-14.8 14.8l13.6 9.2c.1-5.7 4.7-10.3 10.4-10.4");
}

</style>
