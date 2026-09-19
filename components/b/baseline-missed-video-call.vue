<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_1sr1bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-missed-video-call" /></template>
<style>
.d_1sr1bnu {
  fill: currentColor;
  d: path("M17 10.5V7c0-.55-.45-1-1-1H4c-.55 0-1 .45-1 1v10c0 .55.45 1 1 1h12c.55 0 1-.45 1-1v-3.5l4 4v-11zM10 15l-3.89-3.89v2.55H5V9.22h4.44v1.11H6.89l3.11 3.1l4.22-4.22l.78.79z");
}

</style>
