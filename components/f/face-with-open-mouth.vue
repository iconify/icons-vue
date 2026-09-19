<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="fbp0m0b1e"><circle class="dy9u4yopw"/><circle class="zne7fwbye"/><circle class="rl0d2sb8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:face-with-open-mouth" /></template>
<style>
.dy9u4yopw {
  cx: 32px;
  cy: 45.1px;
  r: 7px;
}

.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.rl0d2sb8f {
  cx: 42.7px;
  cy: 25px;
  r: 4.5px;
}

.zne7fwbye {
  cx: 20.2px;
  cy: 25px;
  r: 4.5px;
}

</style>
