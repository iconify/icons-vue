<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-9leq9vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:5g-mobiledata-badge-sharp" /></template>
<style>
.v-9leq9vf {
  fill: currentColor;
  d: path("M1 21V3h22v18zm18-10h-3v2h1v2h-3V9h5V7h-7v10h7zM5 17h6v-6H7V9h4V7H5v6h4v2H5z");
}

</style>
