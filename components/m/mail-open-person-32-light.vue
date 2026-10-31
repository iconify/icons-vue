<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lsiq_lz2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-open-person-32-light" /></template>
<style>
.lsiq_lz2v {
  fill: currentColor;
  d: path("M28.583 24C29.918 24 31 25.102 31 26.438c0 2.023-1.714 4.062-6 4.062s-6-2.032-6-4.062C19 25.103 20.082 24 21.417 24zM13.978 2.54a4 4 0 0 1 3.997-.005l11.452 6.599a1.145 1.145 0 0 1-.016 1.992l-13.168 7.312l-.002-.003a.5.5 0 0 1-.484 0l-12.73-7.073a3 3 0 0 0-.027.406v10.73a3.5 3.5 0 0 0 3.5 3.5h11.025a4 4 0 0 0-.025.44q0 .28.031.56H6.5a4.5 4.5 0 0 1-4.5-4.5v-10.73a4 4 0 0 1 1.999-3.463zM25 15.5a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7M17.476 3.402a3 3 0 0 0-2.998.002L4.499 9.17a3 3 0 0 0-1.163 1.219L16 17.426l12.926-7.174a.145.145 0 0 0 .002-.252z");
}

</style>
