<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbh2bdp2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:horizontal-rule-outline-rounded" /></template>
<style>
.fbh2bdp2z {
  fill: currentColor;
  d: path("M5.5 12.5q-.213 0-.356-.144T5 11.999t.144-.356t.356-.143h13q.213 0 .356.144t.144.357t-.144.356t-.356.143z");
}

</style>
