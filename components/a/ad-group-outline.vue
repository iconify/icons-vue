<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r076qe-ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ad-group-outline" /></template>
<style>
.r076qe-ec {
  fill: currentColor;
  d: path("M8.116 16h10.769q.23 0 .423-.192t.192-.423V6h-12v9.385q0 .23.192.423t.423.192m0 1q-.69 0-1.153-.462T6.5 15.385V4.615q0-.69.463-1.153T8.116 3h10.769q.69 0 1.153.462t.462 1.153v10.77q0 .69-.462 1.152T18.884 17zm-3 3q-.69 0-1.153-.462T3.5 18.385V6.615h1v11.77q0 .23.192.423t.423.192h11.77v1zM7.5 4v12z");
}

</style>
