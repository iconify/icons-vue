<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvpj3mbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:loyalty-outline-sharp" /></template>
<style>
.xvpj3mbrr {
  fill: currentColor;
  d: path("M12.825 22.825L2 12V2h10l10.8 10.85zm0-2.825l7.15-7.15L11.15 4H4v7.15zM6.5 8q.625 0 1.063-.437T8 6.5t-.437-1.062T6.5 5t-1.062.438T5 6.5t.438 1.063T6.5 8m6.5 9.5l3.5-3.5q.275-.275.438-.65t.162-.8q0-.85-.6-1.45t-1.45-.6q-.475 0-.937.275T13 11.7q-.75-.7-1.175-.95t-.875-.25q-.85 0-1.45.6t-.6 1.45q0 .425.163.8T9.5 14z");
}

</style>
