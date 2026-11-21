<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg5ypbu4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flask-conical-ban-sharp" /></template>
<style>
.qg5ypbu4l {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.6753 22L11.0718 22L2.0001 22L7.5 8L7.5 2L12.5 2L12.5 8L13.9705 11.0889L14.4749 12.1487M5 2L6 2L14 2L15 2M1.9649 18L2.7394 18L10 18L11.0718 18M15.1716 15.1716L20.8284 20.8284M18 14C20.2092 14 22 15.7908 22 18C22 20.2092 20.2092 22 18 22C15.7908 22 14 20.2092 14 18C14 15.7908 15.7908 14 18 14Z");
}

</style>
