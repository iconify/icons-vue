<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7t5_o1hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:laptop-mac-outline" /></template>
<style>
.p7t5_o1hx {
  fill: currentColor;
  d: path("M2.27 19.27q-.518 0-.894-.377T1 18h3.616q-.691 0-1.153-.462T3 16.384V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616v10.769q0 .69-.463 1.153T19.385 18H23q0 .517-.376.893t-.893.376zm10.164-.683q.182-.181.182-.433t-.182-.434t-.434-.18t-.434.181t-.182.434q0 .252.182.433t.434.182t.434-.181M4.616 17h14.769q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T19.385 5H4.615q-.23 0-.423.192T4 5.616v10.769q0 .23.192.423t.423.192M4 17V5z");
}

</style>
