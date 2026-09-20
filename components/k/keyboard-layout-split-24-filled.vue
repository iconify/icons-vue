<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nupmqabpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:keyboard-layout-split-24-filled" /></template>
<style>
.nupmqabpe {
  fill: currentColor;
  d: path("M19.745 5a2.25 2.25 0 0 1 2.25 2.25v9.505a2.25 2.25 0 0 1-2.25 2.25H4.25A2.25 2.25 0 0 1 2 16.755V7.25A2.25 2.25 0 0 1 4.25 5zM6.5 16H10a.75.75 0 0 0 0-1.5H6.5a.75.75 0 0 0 0 1.5m7.5 0h3.5a.75.75 0 0 0 0-1.5H14a.75.75 0 0 0 0 1.5m3.5-5a1 1 0 1 0 0 2a1 1 0 0 0 0-2m-2.995 0a1 1 0 1 0 0 2a1 1 0 0 0 0-2m-5 0a1 1 0 1 0 0 2a1 1 0 0 0 0-2m-3 0a1 1 0 1 0 0 2a1 1 0 0 0 0-2M6 8a1 1 0 1 0 0 2a1 1 0 0 0 0-2m2.995 0a1 1 0 1 0 0 2a1 1 0 0 0 0-2m6 0a1 1 0 1 0 0 2a1 1 0 0 0 0-2m3 0a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
