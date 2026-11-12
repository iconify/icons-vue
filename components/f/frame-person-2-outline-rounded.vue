<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elf0oab3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:frame-person-2-outline-rounded" /></template>
<style>
.elf0oab3m {
  fill: currentColor;
  d: path("M18.143 7.857Q18 7.714 18 7.5v-.885q0-.23-.192-.423T17.384 6H14.5q-.213 0-.357-.143T14 5.5t.143-.357T14.5 5h2.885q.69 0 1.152.463T19 6.616V7.5q0 .214-.143.357T18.5 8t-.357-.143M3.5 10q-.213 0-.357-.143T3 9.5V6.616q0-.691.463-1.153T4.615 5H7.5q.214 0 .357.143T8 5.5t-.143.357T7.5 6H4.616q-.231 0-.424.192T4 6.616V9.5q0 .214-.143.357T3.5 10m1.116 9q-.691 0-1.153-.462T3 17.384V14.5q0-.213.143-.357T3.5 14t.357.143T4 14.5v2.885q0 .23.192.423t.423.192H7.5q.214 0 .357.143T8 18.5t-.143.357T7.5 19zm10.475-5.59Q14.5 12.82 14.5 12t.59-1.41T16.5 10t1.41.59t.59 1.41t-.59 1.41t-1.41.59t-1.41-.59M16.5 16q.917 0 1.822.178t1.786.534q.42.167.656.545q.236.377.236.843v.092q0 .349-.23.578t-.578.23h-7.384q-.349 0-.578-.23t-.23-.578V18.1q0-.465.236-.843q.235-.378.656-.546q.843-.355 1.748-.533Q15.544 16 16.5 16");
}

</style>
