<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d_pd5fboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gauge-rotate-315-20-regular" /></template>
<style>
.d_pd5fboy {
  fill: currentColor;
  d: path("M10.533 2.018a8 8 0 1 1-5.972 2.116a.5.5 0 0 1 .68.733a7 7 0 1 0 5.226-1.852a.5.5 0 0 1 .066-.997m-4.91 4.464c-.257-.534.325-1.116.86-.86l.114.068c1.37 1.005 2.75 1.996 4.101 3.027c.333.254.613.472.717.576a1.501 1.501 0 0 1-2.122 2.122c-.104-.104-.322-.384-.576-.717c-.802-1.05-2.24-3.02-3.027-4.101z");
}

</style>
