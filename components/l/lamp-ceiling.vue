<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msjl5oe1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lamp-ceiling" /></template>
<style>
.msjl5oe1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 2L15 2M12 2L12 10M7.7035 10.449C7.8886 10.168 8.202 10 8.5378 10L15.4622 10C15.798 10 16.1114 10.168 16.2965 10.449L19.7489 15.673C20.4079 16.67 19.6928 18 18.4975 18L5.5025 18C4.3072 18 3.5921 16.67 4.2511 15.673L7.7035 10.449ZM8 18C8 20.2091 9.7909 22 12 22C14.2091 22 16 20.2091 16 18");
}

</style>
