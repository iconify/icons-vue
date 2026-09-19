<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0nwlqb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-solar-power" /></template>
<style>
.w0nwlqb7d {
  fill: currentColor;
  d: path("M3.33 16H11v-3H4zM13 16h7.67L20 13h-7zm8.11 2H13v4h9zM2 22h9v-4H2.89zm9-14h2v3h-2zm4.764-.795l1.415-1.414L19.3 7.912l-1.414 1.414zm-11.059.708L6.826 5.79L8.24 7.206L6.12 9.327zM3 2h3v2H3zm15 0h3v2h-3zm-6 5c2.76 0 5-2.24 5-5H7c0 2.76 2.24 5 5 5");
}

</style>
