<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s47kc73dd"/><path class="h89wykbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevron-last-outline" /></template>
<style>
.h89wykbwy {
  fill: currentColor;
  d: path("M7.01174 4.43066C7.32618 4.16116 7.79978 4.19738 8.06936 4.51172L14.0694 11.5117C14.3101 11.7926 14.3101 12.2074 14.0694 12.4883L8.06936 19.4883C7.79978 19.8026 7.32618 19.8388 7.01174 19.5693C6.6974 19.2997 6.66117 18.8262 6.93069 18.5117L12.5117 12L6.93069 5.48828C6.66117 5.17384 6.6974 4.70025 7.01174 4.43066Z");
}

.s47kc73dd {
  fill: currentColor;
  d: path("M16.5 4.25C16.9142 4.25002 17.25 4.5858 17.25 5V19C17.25 19.4142 16.9142 19.75 16.5 19.75C16.0858 19.75 15.75 19.4142 15.75 19V5C15.75 4.58579 16.0858 4.25001 16.5 4.25Z");
}

</style>
