<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijdg2qbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-4-bar-outline-rounded" /></template>
<style>
.ijdg2qbpd {
  fill: currentColor;
  d: path("M8.885 12h6.23V5.462h-6.23zm-.19 9q-.35 0-.58-.232q-.23-.233-.23-.576V5.288q0-.343.232-.575t.575-.232h1.616v-.673q0-.344.232-.576T11.116 3h1.769q.343 0 .575.232t.232.576v.673h1.62q.344 0 .574.232t.23.575v14.904q0 .344-.233.576t-.575.232z");
}

</style>
