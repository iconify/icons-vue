<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="naycjkbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:living-outline-sharp" /></template>
<style>
.naycjkbob {
  fill: currentColor;
  d: path("M3 21V3h18v18zm1-1h16V4H4zm1.616-2.616h12.769V10.35h-1.25V7H6.865v3.35h-1.25zM6.5 16.5v-5.384h2v3h7v-3h2V16.5zm2.885-3.27v-2.95H7.75V7.886h8.5v2.396h-1.634v2.95zM4 20V4z");
}

</style>
