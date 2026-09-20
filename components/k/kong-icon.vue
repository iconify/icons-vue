<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":225};
const content = `<path class="l_ldgf7sb"/><path class="jgbln0b2u"/><path class="zdwikj0la"/><path class="yxsk0o1bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:kong-icon" /></template>
<style>
.jgbln0b2u {
  fill: var(--svg-color--14b59a, #14b59a);
  d: path("m94.559 89.641l21.851-37.749h25.462l114.129 132.566l-8.849 40.408h-48.938l3.07-11.343z");
}

.l_ldgf7sb {
  fill: var(--svg-color--169fcc, #169fcc);
  d: path("m80.721 192.398l6.115-7.893h45.253l23.587 30.136l-4.193 10.225H93.126l1.398-10.225z");
}

.yxsk0o1bo {
  fill: var(--svg-color--16bdcc, #16bdcc);
  d: path("M37.969 129.026h14.216l37.069-31.008l49.125 57.082l-13.856 20.789H79.177l-31.311 39.816l-7.198 9.161H0v-48.801z");
}

.zdwikj0la {
  fill: var(--svg-color--1bc263, #1bc263);
  d: path("m121.082 44.72l10.462-19.348L162.932 0l53.782 42.164l-6.975 7.119l9.361 12.96v13.872l-26.799 21.903L147.33 44.72z");
}

</style>
