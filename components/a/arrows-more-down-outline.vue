<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewwdgpbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrows-more-down-outline" /></template>
<style>
.ewwdgpbmu {
  fill: currentColor;
  d: path("M5 21V10h2v9h9v2zm5-5V5h2v9h9v2z");
}

</style>
