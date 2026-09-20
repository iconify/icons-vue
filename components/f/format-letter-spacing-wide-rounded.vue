<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5ox9x26l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-letter-spacing-wide-rounded" /></template>
<style>
.m5ox9x26l {
  fill: currentColor;
  d: path("M4.143 18.856Q4 18.713 4 18.5v-13q0-.213.144-.356T4.501 5t.356.144T5 5.5v13q0 .213-.144.356T4.499 19t-.356-.144m15 0Q19 18.713 19 18.5v-13q0-.213.144-.356T19.501 5t.356.144T20 5.5v13q0 .213-.144.356t-.357.144t-.356-.144M8.473 17q-.25 0-.398-.206q-.148-.205-.056-.452l3.304-8.946q.06-.145.181-.232q.12-.087.287-.087h.365q.155 0 .278.087t.185.232l3.362 8.933q.092.246-.054.458t-.408.213q-.16 0-.29-.092t-.196-.247l-.892-2.5h-4.34l-.879 2.525q-.047.15-.175.232Q8.62 17 8.473 17m1.66-3.712h3.693l-1.815-5.111h-.062z");
}

</style>
