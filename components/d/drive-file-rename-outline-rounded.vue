<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp6kmgftl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:drive-file-rename-outline-rounded" /></template>
<style>
.lp6kmgftl {
  fill: currentColor;
  d: path("M11.283 16.5h5.833q.213 0 .356-.143q.144-.143.144-.357t-.144-.357t-.357-.143h-4.832zm-4.09 0h1.073q.161 0 .3-.056q.14-.055.27-.186L15.095 10q.129-.148.19-.31q.062-.163.062-.323t-.064-.319t-.188-.308l-.925-.944q-.129-.129-.298-.193t-.335-.064q-.159 0-.319.052q-.16.051-.308.2l-6.282 6.257q-.13.13-.187.27t-.056.301v1.073q0 .349.23.578q.23.23.578.23m7.27-7.133l-.926-.944zM7.27 15.616v-.95l4.685-4.68l.456.489l.469.475l-4.66 4.666zm5.14-5.141l.47.475l-.925-.963zM5.617 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm0-1h12.769q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T18.384 5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192M5 5v14z");
}

</style>
