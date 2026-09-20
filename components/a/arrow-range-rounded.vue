<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkke-vcjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-range-rounded" /></template>
<style>
.pkke-vcjp {
  fill: currentColor;
  d: path("m4.902 12.52l2.76 2.759q.14.146.133.347t-.153.347t-.334.146t-.335-.146l-3.407-3.389q-.131-.13-.184-.267q-.053-.136-.053-.298t.053-.298q.053-.137.184-.267l3.388-3.389q.146-.146.344-.146t.344.146q.166.146.156.357q-.01.21-.156.357L4.922 11.5h14.157l-2.721-2.721q-.14-.146-.153-.357q-.013-.21.153-.357q.146-.146.353-.136q.208.01.355.155l3.369 3.37q.13.13.183.267t.053.298t-.053.298t-.183.268l-3.389 3.388q-.146.146-.334.146t-.354-.146t-.166-.357t.166-.376l2.72-2.72z");
}

</style>
