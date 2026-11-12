<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dymbypvaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:frame-person-2" /></template>
<style>
.dymbypvaf {
  fill: currentColor;
  d: path("M18 8V6.616q0-.231-.192-.424T17.384 6H14V5h3.385q.69 0 1.152.463T19 6.616V8zM3 10V6.616q0-.691.463-1.153T4.615 5H8v1H4.616q-.231 0-.424.192T4 6.616V10zm1.616 9q-.691 0-1.153-.462T3 17.384V14h1v3.385q0 .23.192.423t.423.192H8v1zM12 19v-.9q0-.465.236-.843q.235-.378.656-.546q.843-.355 1.748-.533Q15.544 16 16.5 16q.917 0 1.822.178t1.786.534q.42.167.656.545q.236.377.236.843v.9zm3.09-5.59q-.59-.59-.59-1.41t.59-1.41T16.5 10t1.41.59t.59 1.41t-.59 1.41t-1.41.59t-1.41-.59");
}

</style>
