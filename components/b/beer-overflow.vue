<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv7p8nb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:beer-overflow" /></template>
<style>
.bv7p8nb5k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 13V7.586q-.53-2.383 1.471-3.828q1.7-1.228 3.468-.509q1.023-1.55 3.061-1.55q2.111 0 3.133 1.664q1.628-.332 3.013.794q1.631 1.325 1.354 3.395V9q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T17 9.75h-.25v.5h1.75q2.25 0 2.25 2.25v4q0 2.25-2.25 2.25h-1.75v.75q0 2.25-2.25 2.25h-9q-2.25 0-2.25-2.25v-4.854q-1-.323-1-1.646m2.5 6.5v-4.854q1-.323 1-1.646V9.75h9.5v9.75q0 .75-.75.75h-9q-.75 0-.75-.75m12-2.25h1.75q.75 0 .75-.75v-4q0-.75-.75-.75h-1.75z");
}

</style>
