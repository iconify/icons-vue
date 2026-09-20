<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihi_ylbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:double-arrow" /></template>
<style>
.ihi_ylbpw {
  fill: currentColor;
  d: path("m7.089 18.5l4.653-6.5L7.09 5.5h1.219l4.654 6.5l-4.654 6.5zm5.796 0l4.654-6.5l-4.655-6.5h1.22l4.654 6.5l-4.654 6.5z");
}

</style>
