<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgej9abbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-flow-square-multiple-24-regular" /></template>
<style>
.mgej9abbb {
  fill: currentColor;
  d: path("M19.001 6.01a3.25 3.25 0 0 1 3 3.24v6.5a6.25 6.25 0 0 1-6.25 6.25h-6.5a3.25 3.25 0 0 1-3.24-3h1.51c.12.848.848 1.5 1.73 1.5h6.5a4.75 4.75 0 0 0 4.75-4.75v-6.5c0-.882-.652-1.609-1.5-1.73zM14.75 2A3.25 3.25 0 0 1 18 5.25v9.5A3.25 3.25 0 0 1 14.75 18h-9.5A3.25 3.25 0 0 1 2 14.75V9.868c.235.083.487.132.75.132s.515-.049.75-.132v4.882c0 .966.784 1.75 1.75 1.75h9.5a1.75 1.75 0 0 0 1.75-1.75v-9.5a1.75 1.75 0 0 0-1.75-1.75h-9.5A1.75 1.75 0 0 0 3.5 5.25v.38a2.2 2.2 0 0 0-.75-.13c-.263 0-.515.048-.75.13v-.38A3.25 3.25 0 0 1 5.25 2zm-12 4.5c.409 0 .77.197.998.5H4.6a4.93 4.93 0 0 1 4.01 2.064A3.43 3.43 0 0 0 11.4 10.5h1.04l-1.72-1.72a.75.75 0 1 1 1.06-1.06l3 3a.75.75 0 0 1 0 1.06l-3 3a.75.75 0 1 1-1.06-1.06L12.44 12H11.4a4.93 4.93 0 0 1-4.01-2.064A3.43 3.43 0 0 0 4.6 8.5h-.852a1.25 1.25 0 1 1-.998-2");
}

</style>
