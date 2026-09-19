<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="feui3y4kq"/><path class="he_sxxb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-install-mobile" /></template>
<style>
.feui3y4kq {
  fill: currentColor;
  d: path("M17 18H7V6h7V1H7c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2v-5h-2z");
}

.he_sxxb4l {
  fill: currentColor;
  d: path("m18 14l5-5l-1.41-1.41L19 10.17V3h-2v7.17l-2.59-2.58L13 9z");
}

</style>
