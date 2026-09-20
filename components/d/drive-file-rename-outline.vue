<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9n3_jbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:drive-file-rename-outline" /></template>
<style>
.w9n3_jbxy {
  fill: currentColor;
  d: path("M11.283 16.5h6.333v-1h-5.333zm-4.898 0h2.21l6.5-6.5q.128-.148.19-.31q.061-.163.061-.323t-.064-.319t-.188-.308l-.925-.944q-.129-.129-.298-.193t-.335-.064q-.159 0-.319.052q-.16.051-.308.2l-6.525 6.5zm8.076-7.133l-.925-.944zM7.27 15.616v-.95l4.685-4.68l.456.489l.469.475l-4.66 4.666zm5.14-5.141l.47.475l-.925-.963zM5.617 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm0-1h12.769q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T18.384 5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192M5 5v14z");
}

</style>
