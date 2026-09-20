<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5c1l1b2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cards-star-outline-sharp" /></template>
<style>
.s5c1l1b2r {
  fill: currentColor;
  d: path("m12.34 12.192l1.93-1.163l1.928 1.163l-.523-2.196l1.712-1.475l-2.24-.186l-.878-2.066l-.877 2.066l-2.24.186l1.712 1.475zm4.543 6.27h1.444l.098.825l-13.84 1.742L2.927 8.065l2.612-.254v1L4.1 8.956L5.45 19.9zm-9.344-2V3H21v13.462zm1-1H20V4H8.539zm5.73-5.731");
}

</style>
