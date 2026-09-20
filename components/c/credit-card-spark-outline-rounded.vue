<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d563b2_ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:credit-card-spark-outline-rounded" /></template>
<style>
.d563b2_ke {
  fill: currentColor;
  d: path("M4 18v-7.577v.194V6zm.616 1q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v3.367q0 .373-.301.584t-.649.089q-.396-.104-.808-.168t-.838-.065q-.835 0-1.594.195t-1.433.574H4v6.193q0 .23.192.423t.423.192h7.045q.213 0 .354.143q.14.144.14.357t-.143.357t-.357.143zM4 8.808h16V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616zM18.404 21q-.15 0-.2-.15q-.362-1.39-1.359-2.387t-2.387-1.36q-.15-.05-.15-.2q0-.174.15-.2q1.39-.36 2.387-1.358q.997-.997 1.359-2.387q.05-.15.2-.15q.169 0 .2.15q.361 1.39 1.358 2.387t2.388 1.359q.15.025.15.2q0 .15-.15.2q-1.39.362-2.388 1.359t-1.358 2.387q-.025.15-.2.15");
}

</style>
