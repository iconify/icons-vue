<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-8of7b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flag-check-rounded" /></template>
<style>
.h-8of7b4i {
  fill: currentColor;
  d: path("M6.143 20.357Q6 20.214 6 20V5.808q0-.348.23-.578T6.808 5h3.375q.31 0 .536.235t.235.563q-.006.052-.009.101T10.942 6q.166 2.548 2.011 4.238q1.845 1.689 4.355 1.689q.225 0 .45-.012t.444-.057q.315-.05.557.148q.241.198.241.508v1.678q0 .349-.23.578t-.578.23H14.48q-.292 0-.52-.177q-.226-.177-.282-.47L13.407 13H7v7q0 .214-.143.357T6.5 20.5t-.357-.143m14-17.65q1.165 1.164 1.165 2.835t-1.165 2.836t-2.835 1.164t-2.836-1.164t-1.164-2.836q0-1.67 1.164-2.835q1.165-1.165 2.836-1.165t2.835 1.165m-3.541 3.595l-.988-.988q-.13-.13-.305-.136q-.174-.007-.322.141t-.149.314q0 .165.149.313l1.05 1.05q.242.243.565.243t.565-.243l2.462-2.455q.129-.13.138-.307q.01-.178-.138-.326t-.314-.145t-.313.145z");
}

</style>
