<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gqyfd86vw"/><path class="lkantfb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:katawa-shoujo" /></template>
<style>
.gqyfd86vw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 12.17c12.092-16.05 37.06 6.213 0 29.117m0-29.117c-12.092-16.05-37.06 6.213 0 29.117m13.561-11.054l-4.674-3.773m6.078 2.041l-4.675-3.773");
}

.lkantfb9k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.944 17.199l1.775 1.347m-1.775-1.347l-1.731.987l-.444 2.15l-7.358 8.835l1.396 1.131l7.266-9.006l2.02-.858l.626-1.892M22.966 34.019c.276 2.043 1.598 2.579 3.211 2.63m4.565-5.574l-4.565 5.574m1.354-8.204l-4.565 5.574m4.565-5.574l3.211 2.63m.862-5.871l-2.619-2.07m4.023.338l-2.62-2.07M25.8 16.604l2.022 1.735m-1.917 2.28l1.913-2.27m-3.91.557l2.007 1.721m-.115-4.023a3.456 3.456 0 1 1-2.038 2.205");
}

</style>
