<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3mjccbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:expand-more" /></template>
<style>
.c3mjccbqa {
  fill: currentColor;
  d: path("M12 14.702L6.692 9.394l.708-.707l4.6 4.6l4.6-4.6l.708.707z");
}

</style>
