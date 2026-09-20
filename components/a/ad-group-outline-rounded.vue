<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecjs91bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ad-group-outline-rounded" /></template>
<style>
.ecjs91bqh {
  fill: currentColor;
  d: path("M8.116 16h10.769q.23 0 .423-.192t.192-.423V6h-12v9.385q0 .23.192.423t.423.192m0 1q-.69 0-1.153-.462T6.5 15.385V4.615q0-.69.463-1.153T8.116 3h10.769q.69 0 1.153.462t.462 1.153v10.77q0 .69-.462 1.152T18.884 17zm-3 3q-.69 0-1.153-.462T3.5 18.385V7.115q0-.213.143-.356T4 6.616t.357.143t.143.357v11.269q0 .23.192.423t.423.192h11.27q.213 0 .356.143t.144.357t-.144.357t-.356.143zM7.5 4v12z");
}

</style>
