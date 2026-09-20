<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="sluitbbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:directions-28-filled" /></template>
<style>
.sluitbbrs {
  fill: currentColor;
  d: path("M11.349 2.098a3.75 3.75 0 0 1 5.303 0l9.25 9.253a3.75 3.75 0 0 1 0 5.302l-9.25 9.251a3.75 3.75 0 0 1-5.303 0l-9.251-9.25a3.75 3.75 0 0 1 0-5.303zm4.43 5.122a.75.75 0 0 0-1.06 1.06L16.44 10h-2.69C11.68 10 10 11.68 10 13.75v4.5a.75.75 0 0 0 1.5 0v-4.5a2.25 2.25 0 0 1 2.25-2.25h2.69l-1.72 1.72a.75.75 0 0 0 1.06 1.06l3-3a.75.75 0 0 0 0-1.06z");
}

</style>
