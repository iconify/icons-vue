<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkjcanbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-warning-24-filled" /></template>
<style>
.hkjcanbpq {
  fill: currentColor;
  d: path("M22 11.998c0-5.523-4.477-10-10-10s-10 4.477-10 10a9.96 9.96 0 0 0 1.145 4.65l-1.116 4.289a.85.85 0 0 0 1.036 1.036l4.29-1.117A9.96 9.96 0 0 0 12 21.998c5.523 0 10-4.477 10-10M12 6.5a.75.75 0 0 1 .75.75v6.25a.75.75 0 0 1-1.5 0V7.25A.75.75 0 0 1 12 6.5m1 9.997a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

</style>
