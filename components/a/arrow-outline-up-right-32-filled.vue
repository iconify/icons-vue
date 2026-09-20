<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hyl_xnb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-outline-up-right-32-filled" /></template>
<style>
.hyl_xnb5i {
  fill: currentColor;
  d: path("M9.969 29.125a3 3 0 0 0 4.242 0l6.904-6.904l1.749 1.75c2.122 2.12 5.755.763 5.966-2.23l1.167-16.53a3 3 0 0 0-3.204-3.203L10.26 3.175c-2.994.212-4.35 3.845-2.228 5.967L9.78 10.89l-6.9 6.902a3 3 0 0 0 0 4.243z");
}

</style>
