<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttfdi3b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-arrow-right-24-regular" /></template>
<style>
.ttfdi3b_u {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m-9-3.5H6.25a1.75 1.75 0 0 0-1.75 1.75v7.5c0 .966.784 1.75 1.75 1.75h5l.063-.004q.246.757.658 1.42a3.3 3.3 0 0 1-.721.084h-5A3.25 3.25 0 0 1 3 17.75v-7.5A3.25 3.25 0 0 1 6.25 7H8.5zm9.854 6.147a.5.5 0 1 0-.707.707L19.293 17H14.5a.5.5 0 0 0 0 1h4.793l-1.646 1.646a.5.5 0 1 0 .707.707l2.5-2.5a.5.5 0 0 0 0-.707zM17.75 3A3.25 3.25 0 0 1 21 6.25v5.774a6.5 6.5 0 0 0-1.5-.71V6.25a1.75 1.75 0 0 0-1.75-1.75h-5A1.75 1.75 0 0 0 11 6.25v7.5c0 .48.193.914.506 1.23a6.5 6.5 0 0 0-.435 1.553A3.25 3.25 0 0 1 9.5 13.75v-7.5A3.25 3.25 0 0 1 12.75 3z");
}

</style>
