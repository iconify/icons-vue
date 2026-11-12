<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="raun3xbhc"/><path class="dk3eigbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevron-first-bold-duotone" /></template>
<style>
.dk3eigbon {
  fill: currentColor;
  d: path("M8.25 19C8.25 19.4142 7.9142 19.75 7.5 19.75C7.08579 19.75 6.75 19.4142 6.75 19L6.75 5C6.75 4.58579 7.08579 4.25 7.5 4.25C7.91421 4.25 8.25 4.58579 8.25 5L8.25 19Z");
}

.raun3xbhc {
  fill: currentColor;
  d: path("M15.9308 4.51173C16.2004 4.19741 16.674 4.16116 16.9884 4.43068C17.3027 4.70027 17.3389 5.17388 17.0694 5.48829L11.4884 12L17.0694 18.5117C17.3389 18.8262 17.3027 19.2998 16.9884 19.5693C16.674 19.8388 16.2004 19.8026 15.9308 19.4883L9.93077 12.4883C9.69003 12.2074 9.69003 11.7926 9.93077 11.5117L15.9308 4.51173Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
