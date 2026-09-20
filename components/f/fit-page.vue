<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp_8qgk7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fit-page" /></template>
<style>
.wp_8qgk7e {
  fill: currentColor;
  d: path("M3 21V3h2v18zm16 0V3h2v18zM7 13v-2h2v2zm4 8v-2h2v2zm0-4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm0-4V3h2v2zm4 8v-2h2v2z");
}

</style>
