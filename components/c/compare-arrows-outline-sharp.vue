<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu-1fub_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:compare-arrows-outline-sharp" /></template>
<style>
.yu-1fub_e {
  fill: currentColor;
  d: path("m8 20l-1.4-1.425L9.175 16H2v-2h7.175L6.6 11.425L8 10l5 5zm8-6l-5-5l5-5l1.4 1.425L14.825 8H22v2h-7.175l2.575 2.575z");
}

</style>
