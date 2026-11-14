<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqqm27b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:easter-eggs-basket" /></template>
<style>
.zqqm27b2x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.728 11.25h.772q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .105-.029.206l-1.997 6.991q-.551 2.116-2.735 2.053H6.511q-2.184.063-2.735-2.053l-1.997-6.991q-.041-.143-.024-.292q.017-.148.089-.278q.073-.131.19-.223q.117-.093.26-.134q.101-.029.206-.029h.772q.226-3.703 2.721-5.99Q8.458 3 12 3t6.007 2.26q2.495 2.287 2.721 5.99m-15.952 0q.217-3.038 2.231-4.885Q9.042 4.5 12 4.5t4.993 1.865q2.014 1.847 2.231 4.885h-1.25q-.225-3-2.349-3q-.838 0-1.38.467Q13.571 7.125 12 7.125T9.755 8.717q-.542-.467-1.38-.467q-2.124 0-2.349 3zm10.003 0h1.692q-.132-1.5-.846-1.5t-.846 1.5M12 8.625q1.102 0 1.233 2.625h-2.466Q10.898 8.625 12 8.625M9.221 11.25q-.132-1.5-.846-1.5t-.846 1.5z");
}

</style>
