<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xocvwubfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cursor-off-sharp" /></template>
<style>
.xocvwubfc {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.2925 7.2925L2 9.1543L10.7742 12.919L15.1372 22L16.8479 16.8479L7.2925 7.2925ZM17.9107 13.5099L18.214 12.5572L21.3839 2.601L11.5364 5.8795L10.5877 6.1957M1.7071 1.7071L22.2929 22.2929");
}

</style>
