<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zup1l2byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flag-check" /></template>
<style>
.zup1l2byh {
  fill: currentColor;
  d: path("M6 20.5V5h4.98q-.028.148-.042.274t-.015.268q0 2.737 1.908 4.561t4.477 1.824q.423 0 .846-.046t.846-.177V15h-5.192l-.4-2H7v7.5zM20.143 2.707q1.165 1.164 1.165 2.835t-1.165 2.836t-2.835 1.164t-2.836-1.164t-1.164-2.836q0-1.67 1.164-2.835q1.165-1.165 2.836-1.165t2.835 1.165m-3.541 4.855l3.34-3.335l-.626-.627l-2.714 2.702L15.3 5l-.627.633z");
}

</style>
