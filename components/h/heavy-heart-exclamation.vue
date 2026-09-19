<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="ic-371bqb"><circle class="mkh42eq1j"/><path class="hanhec7re"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:heavy-heart-exclamation" /></template>
<style>
.hanhec7re {
  d: path("M57.4 11.8C52.9-2.7 34.3 1.2 32 8.9C29.7 1.2 11.1-2.7 6.6 11.8C4.6 18.1 7.7 24 13 27.7c7.1 5 15.5 5 19 14.3c3.5-9.3 11.8-9.3 19-14.3c5.3-3.7 8.4-9.6 6.4-15.9");
}

.ic-371bqb {
  fill: var(--svg-color--ff5a79, #ff5a79);
}

.mkh42eq1j {
  cx: 32px;
  cy: 52px;
  r: 10px;
}

</style>
