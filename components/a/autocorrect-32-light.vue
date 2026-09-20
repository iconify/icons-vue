<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h85k3qb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:autocorrect-32-light" /></template>
<style>
.h85k3qb1u {
  fill: currentColor;
  d: path("M13.895 7.15c.983-1.534 3.226-1.534 4.21 0L21.852 13H19.5a6.5 6.5 0 1 0 5.256 2.675L23.682 14H29.5a.5.5 0 1 0 0-1h-6.46l-4.095-6.389c-1.377-2.148-4.516-2.148-5.893 0L2.079 23.731a.5.5 0 0 0 .842.54zm10.037 9.092l.384.6a5.5 5.5 0 1 1-.385-.6");
}

</style>
