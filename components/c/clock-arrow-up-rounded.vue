<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-gz9-bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:clock-arrow-up-rounded" /></template>
<style>
.y-gz9-bts {
  fill: currentColor;
  d: path("M4.207 16.438q-1.86-1.87-1.86-4.534t1.86-4.534T8.73 5.5t4.534 1.87t1.87 4.534t-1.87 4.534t-4.534 1.87t-4.524-1.87m5.043-4.705v-3.04q0-.214-.143-.358t-.357-.143t-.357.143t-.143.357v3.171q0 .162.056.302t.186.27l2.192 2.192q.16.16.355.15t.353-.15q.16-.16.16-.363q0-.204-.16-.364zm9.635-4.817l-1.37 1.369q-.16.16-.353.16t-.354-.16t-.16-.354t.16-.354l2.011-2.011q.243-.243.566-.243t.565.243l2.012 2.011q.16.165.16.357t-.166.35q-.166.16-.357.163t-.351-.162L19.884 6.92V18.5q0 .214-.143.357t-.356.143t-.357-.143t-.143-.357z");
}

</style>
