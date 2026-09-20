<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnwkdpi4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-cool-down-outline-rounded" /></template>
<style>
.mnwkdpi4p {
  fill: currentColor;
  d: path("M11.702 20.864q-.136-.056-.267-.187l-5.427-5.421q-.14-.14-.15-.344t.13-.35q.146-.166.357-.156q.21.01.357.156l4.798 4.784V12.73q0-.213.144-.356t.357-.144t.356.144t.143.356v6.637l4.823-4.804q.136-.14.339-.14t.353.145q.137.134.137.341t-.14.348l-5.446 5.421q-.132.13-.27.187t-.298.055t-.296-.055m-.059-10.779q-.143-.144-.143-.356v-2q0-.213.144-.356t.357-.144t.356.144t.143.356v2.019q0 .205-.144.343t-.357.138t-.356-.144m0-5q-.143-.144-.143-.356v-1q0-.213.144-.357t.357-.143t.356.143t.143.357v1.019q0 .204-.144.342t-.357.139t-.356-.144");
}

</style>
