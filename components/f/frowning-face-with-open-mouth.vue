<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="fbp0m0b1e"><circle class="i3dp_0b1d"/><circle class="xxje09bfz"/><path class="ql3dwacot"/></g><path class="gftukgbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:frowning-face-with-open-mouth" /></template>
<style>
.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.gftukgbor {
  fill: var(--svg-color--fff, #fff);
  d: path("M42 43c.1-.3 0-.6-.2-.8c0 0-2.2-2.2-9.8-2.2c-7.5 0-9.8 2.2-9.8 2.2c-.2.1-.2.5-.2.8l.2.6c.1.3.3.5.6.5h18.4c.2 0 .5-.2.6-.5z");
}

.i3dp_0b1d {
  cx: 20.5px;
  cy: 26px;
  r: 5px;
}

.ql3dwacot {
  d: path("M45.7 44c-1.5-3.6-5.1-6-13.7-6s-12.2 2.4-13.7 6c-.8 1.9.3 4 .3 4c.4 1.2 2.2 2 13.4 2c11.1 0 12.9-.8 13.4-2c0 0 1.1-2.1.3-4");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.xxje09bfz {
  cx: 43.5px;
  cy: 26px;
  r: 5px;
}

</style>
