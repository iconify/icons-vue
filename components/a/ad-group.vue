<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be-fiy_fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ad-group" /></template>
<style>
.be-fiy_fx {
  fill: currentColor;
  d: path("M8.116 17q-.691 0-1.153-.462T6.5 15.385V4.615q0-.69.463-1.153T8.116 3h10.769q.69 0 1.153.462t.462 1.153v10.77q0 .69-.462 1.152T18.884 17zM7.5 6h12V4.616q0-.231-.192-.424T18.884 4H8.116q-.231 0-.424.192t-.192.423zM5.116 20q-.691 0-1.153-.462T3.5 18.385V6.615h1v11.77q0 .23.192.423t.423.192h11.77v1z");
}

</style>
