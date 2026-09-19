<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="ic-371bqb"><path class="cuyyezbxs"/><ellipse class="o-hj8qbbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:exclamation-mark" /></template>
<style>
.cuyyezbxs {
  d: path("M37 42.4H27L23 2h18z");
}

.ic-371bqb {
  fill: var(--svg-color--ff5a79, #ff5a79);
}

.o-hj8qbbo {
  cx: 32px;
  cy: 54.4px;
  rx: 7.7px;
  ry: 7.6px;
}

</style>
