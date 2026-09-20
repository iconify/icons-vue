<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5_j2-b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:link" /></template>
<style>
.q5_j2-b1e {
  fill: var(--svg-color--2e61de, #2e61de);
  d: path("m12 3l7.234 4.333V16.1L10.967 21v-1.235L4.784 16.07l-.017-8.685zm.01 14.98l5.157-3.054v-6.42l-5.166-3.092l-5.167 3.132v6.35z");
}

</style>
