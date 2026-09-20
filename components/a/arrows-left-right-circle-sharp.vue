<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqrq81_td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrows-left-right-circle-sharp" /></template>
<style>
.qqrq81_td {
  fill: currentColor;
  d: path("M8.494 20.299q-1.642-.701-2.867-1.926t-1.926-2.867T3 12t.701-3.506t1.926-2.857T8.494 3.71T12 3t3.506.71t2.857 1.927t1.926 2.857T21 12t-.71 3.506t-1.926 2.867t-2.858 1.926T12 21t-3.506-.701m1.16-5.126l.688-.708L8.396 12.5h7.227l-1.946 1.966l.708.707L17.519 12l-3.134-3.154l-.708.708l1.946 1.946H8.396l1.946-1.946l-.688-.708L6.5 12z");
}

</style>
