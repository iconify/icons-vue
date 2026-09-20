<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dff__diaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:category-rounded" /></template>
<style>
.dff__diaa {
  fill: currentColor;
  d: path("m8.637 8.994l2.667-4.402q.13-.211.308-.295q.177-.084.388-.084t.389.084t.307.295l2.668 4.402q.13.202.13.424t-.105.409t-.285.295t-.417.109H9.314q-.239 0-.418-.109q-.179-.108-.284-.29t-.106-.404t.13-.434m8.869 12.237q-1.553 0-2.644-1.087t-1.092-2.64t1.087-2.644q1.087-1.09 2.64-1.09q1.552 0 2.644 1.086q1.09 1.087 1.09 2.64q0 1.552-1.086 2.644q-1.087 1.09-2.64 1.09M3.77 19.923v-4.85q0-.343.232-.573q.233-.23.576-.23h4.85q.344 0 .574.232q.23.233.23.577v4.85q0 .343-.233.573q-.232.23-.576.23h-4.85q-.343 0-.573-.233q-.23-.232-.23-.576");
}

</style>
