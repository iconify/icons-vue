<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2_fj-ull"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard" /></template>
<style>
.c2_fj-ull {
  fill: currentColor;
  d: path("M4.616 18q-.691 0-1.153-.462T3 16.384V7.616q0-.691.463-1.153T4.615 6h14.77q.69 0 1.152.463T21 7.616v8.769q0 .69-.463 1.153T19.385 18zm3.615-2.23h7.538v-1.54H8.231zm-3-3h1.538v-1.54H5.231zm3 0h1.538v-1.54H8.231zm3 0h1.538v-1.54h-1.538zm3 0h1.538v-1.54h-1.538zm3 0h1.538v-1.54h-1.538zm-12-3h1.538V8.23H5.231zm3 0h1.538V8.23H8.231zm3 0h1.538V8.23h-1.538zm3 0h1.538V8.23h-1.538zm3 0h1.538V8.23h-1.538z");
}

</style>
