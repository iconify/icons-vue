<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwyfybc7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:conversation-rounded" /></template>
<style>
.rwyfybc7h {
  fill: currentColor;
  d: path("M6.282 10.283q.218-.217.218-.532q0-.314-.217-.533T5.75 9t-.533.217T5 9.75t.217.533t.532.218t.533-.217m12.5 0Q19 10.066 19 9.75q0-.314-.217-.533Q18.566 9 18.25 9q-.314 0-.533.217q-.218.217-.218.532t.217.533t.532.218t.533-.217M20 19h-2.384q-.499 0-.894-.28t-.549-.72H17q1.458 0 2.479-1.021T20.5 14.5h-1q0 1.031-.734 1.766Q18.03 17 17 17h-1v-3h-1.961q-.385 0-.637-.31q-.252-.311-.152-.691l1.036-4.105q.598-2.436 2.501-4.165T21.167 3q.346 0 .59.232t.243.576V20q0 .417-.291.708q-.291.292-.707.292t-.709-.292T20 20zM4 19v1q0 .417-.291.708q-.291.292-.707.292t-.709-.292T2 20V3.808q0-.344.244-.576T2.833 3q2.477 0 4.38 1.729t2.5 4.165l1.037 4.104q.1.38-.152.692q-.252.31-.636.31H8v3H7q-1.031 0-1.766-.734Q4.5 15.53 4.5 14.5h-1q0 1.458 1.021 2.479T7 18h.827q-.154.44-.549.72t-.893.28z");
}

</style>
