<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urbb0o_je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote-plus" /></template>
<style>
.urbb0o_je {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 12L22 4C22 2.8954 21.1046 2 20 2L4 2C2.8954 2 2 2.8954 2 4L2 14C2 15.1046 2.8954 16 4 16L12 16M14 9C14 10.1046 13.1046 11 12 11C10.8954 11 10 10.1046 10 9C10 7.8954 10.8954 7 12 7C13.1046 7 14 7.8954 14 9ZM17 6L18 6M7 12L6 12M19 16V22M22 19H16");
}

</style>
