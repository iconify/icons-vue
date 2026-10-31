<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pceanw55e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:color-line-32-light" /></template>
<style>
.pceanw55e {
  fill: currentColor;
  d: path("M25.5 19a4.5 4.5 0 0 1 4.5 4.5v2a4.5 4.5 0 0 1-4.5 4.5h-19A4.5 4.5 0 0 1 2 25.5v-2a4.5 4.5 0 0 1 3.88-4.457l-.236 1.063A3.5 3.5 0 0 0 3 23.5v2A3.5 3.5 0 0 0 6.5 29h19a3.5 3.5 0 0 0 3.5-3.5v-2a3.5 3.5 0 0 0-3.5-3.5h-7.923l1-1zM22.433 2a4.566 4.566 0 0 1 3.228 7.794l-9.84 9.84a4 4 0 0 1-1.957 1.076l-5.64 1.259a1 1 0 0 1-1.193-1.194l1.258-5.64a4 4 0 0 1 1.075-1.958l9.84-9.84A4.57 4.57 0 0 1 22.433 2m0 1c-.946 0-1.853.375-2.522 1.044l-9.84 9.84a3 3 0 0 0-.806 1.468l-1.258 5.641l5.64-1.26a3 3 0 0 0 1.467-.806l9.84-9.84A3.567 3.567 0 0 0 22.433 3");
}

</style>
