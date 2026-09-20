<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="mvq5liqlj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:image-prohibited-28-regular" /></template>
<style>
.mvq5liqlj {
  fill: currentColor;
  d: path("M21.25 3A3.75 3.75 0 0 1 25 6.75v14.5A3.75 3.75 0 0 1 21.25 25H6.75A3.75 3.75 0 0 1 3 21.25v-7.751c.461.347.965.64 1.5.874v6.877c0 .361.085.703.236 1.005l7.866-7.688a2 2 0 0 1 2.796 0l7.866 7.688c.15-.302.236-.644.236-1.005V6.75a2.25 2.25 0 0 0-2.25-2.25h-6.876A7.5 7.5 0 0 0 13.5 3zm-6.9 12.64a.5.5 0 0 0-.7 0l-7.835 7.657c.285.13.601.203.935.203h14.5c.333 0 .65-.073.935-.203zM7.5 1a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13M4.534 11.526a5 5 0 0 0 6.992-6.992zM7.5 2.5a5 5 0 0 0-4.026 7.966l6.992-6.992A4.98 4.98 0 0 0 7.5 2.5m11 5a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5m0 1.5a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
