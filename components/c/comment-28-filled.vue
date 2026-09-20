<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="p9xm88lae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-28-filled" /></template>
<style>
.p9xm88lae {
  fill: currentColor;
  d: path("M5.75 3A3.75 3.75 0 0 0 2 6.75v10.5A3.75 3.75 0 0 0 5.75 21H7v3.296c0 1.427 1.616 2.254 2.774 1.419L16.309 21h5.941A3.75 3.75 0 0 0 26 17.25V6.75A3.75 3.75 0 0 0 22.25 3z");
}

</style>
