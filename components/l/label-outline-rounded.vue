<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snj3arbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:label-outline-rounded" /></template>
<style>
.snj3arbyd {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h11q.475 0 .9.213t.7.587l4.5 6q.4.525.4 1.2t-.4 1.2l-4.5 6q-.275.375-.7.588T15 20zm0-2h11l4.5-6L15 6H4zm7.75-6");
}

</style>
