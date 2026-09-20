<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmpqo8bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:data-table-outline-rounded" /></template>
<style>
.pmpqo8bpr {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zM5 8.998h14V5.616q0-.231-.192-.424T18.384 5H5.616q-.231 0-.424.192T5 5.616zm0 5.004h14V9.998H5zM5.616 19h12.769q.23 0 .423-.192t.192-.424v-3.382H5v3.382q0 .231.192.424t.423.192M7 7.574q-.23-.23-.23-.578T7 6.418t.578-.23t.578.23t.23.578t-.23.578t-.578.23T7 7.574m0 5.004q-.23-.23-.23-.578t.23-.578t.578-.23t.578.23t.23.578t-.23.578t-.578.23t-.578-.23m0 5.004q-.23-.23-.23-.578t.23-.578t.578-.23t.578.23t.23.578t-.23.578t-.578.23t-.578-.23");
}

</style>
