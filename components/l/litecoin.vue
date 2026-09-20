<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si5fikblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:litecoin" /></template>
<style>
.si5fikblj {
  fill: var(--svg-color--345d9d, #345d9d);
  d: path("m5.734 15.611l-1.609.63l.776-3.116l1.62-.652L8.86 3h5.772l-1.71 6.975l1.586-.642l-.765 3.083l-1.598.653l-.956 4.074h8.685L18.896 21H4.406z");
}

</style>
