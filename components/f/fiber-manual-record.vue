<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asiw-ubyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fiber-manual-record" /></template>
<style>
.asiw-ubyv {
  fill: currentColor;
  d: path("M7.749 16.255Q6 14.509 6 12.004t1.745-4.255T11.996 6t4.255 1.745Q18 9.491 18 11.996t-1.745 4.255T12.004 18t-4.255-1.745");
}

</style>
