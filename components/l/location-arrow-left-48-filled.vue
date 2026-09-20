<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="axkuoj6ng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:location-arrow-left-48-filled" /></template>
<style>
.axkuoj6ng {
  fill: currentColor;
  d: path("M37 32L26.912 42.71a4 4 0 0 1-5.824 0L11 32h.038l-.017-.02l-.021-.025A16.92 16.92 0 0 1 7 21c0-9.389 7.611-17 17-17s17 7.611 17 17a16.92 16.92 0 0 1-4 10.955l-.021.025l-.017.02zM22.884 16.884a1.25 1.25 0 0 0-1.768-1.768l-5 5a1.25 1.25 0 0 0 0 1.768l5 5a1.25 1.25 0 0 0 1.768-1.768l-2.866-2.866H31a1.25 1.25 0 1 0 0-2.5H20.018z");
}

</style>
