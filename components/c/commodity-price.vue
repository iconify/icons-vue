<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysysn_b5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:commodity-price" /></template>
<style>
.ysysn_b5p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 18q0 1.873 1.198 3.25H8.5q-5.75 0-5.75-4.75q0-7.163 4.805-10.301L6.311 3.295q-.059-.137-.061-.286t.054-.288q.055-.138.159-.245t.242-.165Q6.846 2.25 7 2.25h9q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .154-.061.295l-1.244 2.904q3.568 2.33 4.487 6.88Q19.482 13 19 13h-2q-2.071 0-3.536 1.464Q12 15.929 12 18m2.005-12.25l.858-2H8.137l.858 2zM17 14.25q-3.75 0-3.75 3.75T17 21.75h2q3.75 0 3.75-3.75T19 14.25zM14.75 18q0-2.25 2.25-2.25T19.25 18T17 20.25T14.75 18m6.5 0q0 1.371-.835 1.906q.335-.785.335-1.906t-.335-1.906q.835.535.835 1.906M17 17q-1 0-1 1t1 1t1-1t-1-1");
}

</style>
