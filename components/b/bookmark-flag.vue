<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvlyhbcff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-flag" /></template>
<style>
.kvlyhbcff {
  fill: currentColor;
  d: path("M9.808 13.692h.884v-3h4.193L13.615 9l1.27-1.692H9.808zM6 19.5V5.616q0-.691.463-1.153T7.616 4h8.769q.69 0 1.153.463T18 5.616V19.5l-6-2.577z");
}

</style>
