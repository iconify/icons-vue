<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9lfw0asw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flag-check-outline-rounded" /></template>
<style>
.h9lfw0asw {
  fill: currentColor;
  d: path("M6.143 20.357Q6 20.214 6 20V5.808q0-.348.23-.578T6.808 5h3.663q.214 0 .357.143q.143.144.143.357t-.143.357Q10.685 6 10.471 6H7v6h6.579q.292 0 .519.177t.283.47L14.65 14H18v-1.796q0-.214.143-.357t.357-.143t.357.143t.143.357v1.988q0 .348-.23.578t-.578.23H14.48q-.292 0-.52-.177q-.226-.177-.282-.47L13.407 13H7v7q0 .214-.143.357T6.5 20.5t-.357-.143m14-17.65q1.165 1.164 1.165 2.835t-1.165 2.836t-2.835 1.164t-2.836-1.164t-1.164-2.836q0-1.67 1.164-2.835q1.165-1.165 2.836-1.165t2.835 1.165m-3.541 3.595l-.988-.988q-.13-.13-.305-.136q-.174-.007-.322.141t-.149.314q0 .165.149.313l1.05 1.05q.242.243.565.243t.565-.243l2.462-2.455q.129-.13.138-.307q.01-.178-.138-.326t-.314-.145t-.313.145z");
}

</style>
