<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="eu8ynmbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:luggage-28-filled" /></template>
<style>
.eu8ynmbpt {
  fill: currentColor;
  d: path("M9 2.25a.75.75 0 0 1 .75-.75h8.5a.75.75 0 0 1 0 1.5H18v1h1.5A3.5 3.5 0 0 1 23 7.5V21a3.5 3.5 0 0 1-3 3.465v.785a.75.75 0 0 1-1.5 0v-.75h-9v.75a.75.75 0 0 1-1.5 0v-.785A3.5 3.5 0 0 1 5 21V7.5A3.5 3.5 0 0 1 8.5 4H10V3h-.25A.75.75 0 0 1 9 2.25m2.5.75v1h5V3zM9.75 9a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5z");
}

</style>
