<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="np8th6blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:e-mobiledata-rounded" /></template>
<style>
.np8th6blo {
  fill: currentColor;
  d: path("M9 17q-.213 0-.356-.144T8.5 16.5v-9q0-.213.144-.356T9 7h6q.213 0 .356.144t.144.357t-.144.356T15 8H9.5v3.5H15q.213 0 .356.144t.144.357t-.144.356T15 12.5H9.5V16H15q.213 0 .356.144t.144.357t-.144.356T15 17z");
}

</style>
