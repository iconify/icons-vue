<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0prbgdln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-arrow-right-sharp-fill" /></template>
<style>
.r0prbgdln {
  fill: currentColor;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM11.1062 8.4224L13.7529 11L7 11L7 13L13.7529 13L11.1061 15.577L12.5016 17.0106L16.9111 12.7164C17.3141 12.3238 17.3141 11.6762 16.9111 11.2836L12.5017 6.9888L11.1062 8.4224Z");
}

</style>
