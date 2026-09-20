<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ne_hlpksf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:label-rounded" /></template>
<style>
.ne_hlpksf {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h11q.475 0 .9.213t.7.587l4.5 6q.4.525.4 1.2t-.4 1.2l-4.5 6q-.275.375-.7.588T15 20z");
}

</style>
