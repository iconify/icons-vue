<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpp3cisye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-letter-spacing-wider-rounded" /></template>
<style>
.kpp3cisye {
  fill: currentColor;
  d: path("M3.5 19q-.214 0-.357-.144T3 18.5v-13q0-.213.144-.356T3.501 5t.356.144T4 5.5v13q0 .213-.144.356T3.499 19m16.644-.144Q20 18.713 20 18.5v-13q0-.213.144-.356T20.501 5t.356.144T21 5.5v13q0 .213-.144.356t-.357.144t-.356-.144M8.473 17q-.25 0-.398-.206q-.148-.205-.056-.452l3.304-8.946q.06-.145.181-.232q.12-.087.287-.087h.365q.155 0 .278.087t.185.232l3.362 8.933q.092.246-.054.458t-.408.213q-.16 0-.29-.092t-.196-.247l-.892-2.5h-4.34l-.879 2.525q-.047.15-.175.232Q8.62 17 8.473 17m1.66-3.712h3.693l-1.815-5.111h-.062z");
}

</style>
