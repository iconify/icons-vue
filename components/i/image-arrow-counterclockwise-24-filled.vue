<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr74ttb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:image-arrow-counterclockwise-24-filled" /></template>
<style>
.pr74ttb6u {
  fill: currentColor;
  d: path("M11.559 13.647a.75.75 0 0 1 .873-.007l.093.078l6.928 6.8A3.24 3.24 0 0 1 17.75 21H6.25a3.24 3.24 0 0 1-1.703-.481l6.928-6.801zM17.75 3A3.25 3.25 0 0 1 21 6.25v11.5a3.24 3.24 0 0 1-.485 1.709l-6.939-6.811l-.129-.118a2.25 2.25 0 0 0-2.887-.006l-.136.124l-6.939 6.811A3.24 3.24 0 0 1 3 17.75v-5.771A6.5 6.5 0 0 0 11.979 3zM6.5 1a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m9.252 5a2.252 2.252 0 1 0 0 4.504a2.252 2.252 0 0 0 0-4.504M6.501 3A3.5 3.5 0 0 0 4 4.05V3.5a.5.5 0 0 0-1 0v2a.5.5 0 0 0 .5.5h2a.5.5 0 0 0 0-1h-.999a2.5 2.5 0 1 1 .179 3.214A.64.64 0 0 0 4.222 8c-.41 0-.672.427-.409.742A3.5 3.5 0 1 0 6.501 3m9.251 4.5a.752.752 0 1 1 0 1.504a.752.752 0 0 1 0-1.504");
}

</style>
