<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz3i0i-ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-multiple-24-filled" /></template>
<style>
.kz3i0i-ha {
  fill: currentColor;
  d: path("M20.493 8.508a3.25 3.25 0 0 1 1.508 2.742v4a5.75 5.75 0 0 1-5.75 5.75h-8.5a3.25 3.25 0 0 1-2.743-1.508q.12.008.243.008h11a4.25 4.25 0 0 0 4.25-4.25v-6.5q0-.122-.008-.242M16.251 5.5A3.25 3.25 0 0 1 19.5 8.75v6.5a3.25 3.25 0 0 1-3.25 3.25h-11A3.25 3.25 0 0 1 2 15.25V9.5h5.393a2.24 2.24 0 0 0 1.565-.635c.796-.776 2.53-2.477 3.368-3.365zM7.406 3c.572 0 1.126.217 1.543.618a61 61 0 0 1 1.583 1.576c-.86.871-1.998 1.99-2.62 2.597a.74.74 0 0 1-.52.209H2V6.25A3.25 3.25 0 0 1 5.25 3z");
}

</style>
