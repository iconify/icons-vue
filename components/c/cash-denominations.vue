<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlniefeya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cash-denominations" /></template>
<style>
.wlniefeya {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.25 7.257V4.5q0-.932-.659-1.591T14 2.25H4q-2.25 0-2.25 2.25v4q0 2.25 2.25 2.25h1.25v2.75q0 2.25 2.25 2.25h3.261q-.011.182-.011.375v.75q0 3.375 3.375 3.375h4.75q3.375 0 3.375-3.375v-.75q0-3.375-3.375-3.375h-.625V9.5q0-2.121-2-2.243m-7.5-.007H7.5q-2.121 0-2.243 2H4q-.75 0-.75-.75v-4q0-.75.75-.75h4.75q-2.5 0-2.5 1.75t2.5 1.75m6 0h-6q2.5 0 2.5-1.75t-2.5-1.75H14q.75 0 .75.75zm-8 2.25q0-.75.75-.75H16q.75 0 .75.75v3.25h-2.625q-2.25 0-3 1.5H7.5q-.75 0-.75-.75zm3 0q-2.5 0-2.5 1.75T9.75 13t2.5-1.75t-2.5-1.75m4 7q0-2 2.75-2t2.75 2t-2.75 2t-2.75-2");
}

</style>
