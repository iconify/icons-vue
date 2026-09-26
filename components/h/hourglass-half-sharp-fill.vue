<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jhtts14ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hourglass-half-sharp-fill" /></template>
<style>
.jhtts14ta {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 3L4 3L3 3L3 1L21 1L21 3L19 3L19 7C19 7.2968 18.8682 7.5782 18.6402 7.7682L13.562 12L18.6402 16.2318C18.8682 16.4218 19 16.7032 19 17L19 21L21 21L21 23L3 23L3 21L5 21L5 17C5 16.7032 5.1318 16.4218 5.3598 16.2318L10.438 12L5.3598 7.7682C5.1318 7.5782 5 7.2968 5 7ZM7 3L7 6.5316L7.562 7L16.438 7L17 6.5316L17 3ZM12 13.3017L7.562 17L16.438 17Z");
}

</style>
