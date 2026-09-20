<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="aajas814a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:image-prohibited-28-filled" /></template>
<style>
.aajas814a {
  fill: currentColor;
  d: path("M13.65 15.64a.5.5 0 0 1 .7 0l8.952 8.75c-.59.386-1.295.61-2.052.61H6.75a3.73 3.73 0 0 1-2.052-.61zM21.25 3A3.75 3.75 0 0 1 25 6.75v14.5c0 .771-.233 1.488-.632 2.084l-8.97-8.767a2 2 0 0 0-2.796 0l-8.97 8.767A3.73 3.73 0 0 1 3 21.25v-7.751A7.5 7.5 0 0 0 13.5 3zM18.5 7.75a2.25 2.25 0 1 0 0 4.5a2.25 2.25 0 0 0 0-4.5M7.5 1a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13M4.534 11.526a5 5 0 0 0 6.992-6.992zM7.5 2.5a5 5 0 0 0-4.026 7.966l6.992-6.992A4.98 4.98 0 0 0 7.5 2.5");
}

</style>
