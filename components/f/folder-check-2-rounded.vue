<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evzz98bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-check-2-rounded" /></template>
<style>
.evzz98bfr {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h4.31q.323 0 .628.13q.305.132.522.349L11.596 7h7.789q.69 0 1.153.463T21 8.616v2.867q0 .333-.287.489q-.286.157-.575.009q-.644-.327-1.354-.5t-1.476-.173q-1.402 0-2.62.554q-1.219.553-2.082 1.497t-1.32 2.195q-.455 1.252-.351 2.648q.03.315-.168.557q-.198.241-.507.241zm9.856 1.528q-1.164-1.164-1.164-2.836q0-1.67 1.164-2.835q1.165-1.165 2.836-1.165t2.835 1.165t1.165 2.835t-1.165 2.836t-2.835 1.164t-2.836-1.164m1.565-1.382q.242.242.565.242t.565-.242l2.462-2.456q.129-.129.138-.306q.01-.178-.138-.326t-.314-.146t-.313.146l-2.4 2.394l-.989-.989q-.129-.129-.304-.135t-.323.141t-.148.314t.148.313z");
}

</style>
