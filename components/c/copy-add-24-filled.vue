<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycnz45bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-add-24-filled" /></template>
<style>
.ycnz45bth {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m-9 1.75a4.25 4.25 0 0 0 2.503 3.874a6.47 6.47 0 0 0 1.557 4.099a3.2 3.2 0 0 1-1.31.277h-6A3.25 3.25 0 0 1 2 18.75v-8.5A3.25 3.25 0 0 1 5.25 7H8.5zm9 .249a.5.5 0 0 0-.5.5V17h-2.505a.5.5 0 0 0 0 1h2.506v2.504a.5.5 0 0 0 1 0V18h2.496a.5.5 0 0 0 0-1H18v-2.501a.5.5 0 0 0-.5-.5M18.75 2A3.25 3.25 0 0 1 22 5.25v7.562a6.502 6.502 0 0 0-10.929 3.722A3.25 3.25 0 0 1 9.5 13.75v-8.5A3.25 3.25 0 0 1 12.75 2z");
}

</style>
