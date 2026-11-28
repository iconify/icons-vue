<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxaqfabal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-lock-sharp" /></template>
<style>
.nxaqfabal {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 11L20 8L14 2L4 2L4 22L10 22M14 2L14 8L20 8M13 18L20 18L20 22L13 22ZM14.5 18L14.5 16C14.5 14.8954 15.3954 14 16.5 14C17.6046 14 18.5 14.8954 18.5 16L18.5 18");
}

</style>
