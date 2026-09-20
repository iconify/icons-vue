<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kds_a0bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:heart-off-16-filled" /></template>
<style>
.kds_a0bsb {
  fill: currentColor;
  d: path("m10.452 11.16l3.694 3.694a.5.5 0 0 0 .708-.708l-13-13a.5.5 0 1 0-.708.708l1.946 1.945q-.075.066-.146.137a3.25 3.25 0 0 0 .012 4.595l4.707 4.708a.5.5 0 0 0 .707 0zm2.603-2.602l-1.188 1.188l-6.754-6.754a3.26 3.26 0 0 1 2.428.956l.454.453l.447-.448a3.25 3.25 0 0 1 4.6.012a3.25 3.25 0 0 1 .013 4.593");
}

</style>
