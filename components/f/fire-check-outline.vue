<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2l05qklm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fire-check-outline" /></template>
<style>
.h2l05qklm {
  fill: currentColor;
  d: path("m16.24 21l-2.742-2.723l.708-.708l2.029 2.029l4.057-4.057l.708.713zm-5.555-2.154l1.148 1.148q-.03 0-.061.003t-.06.003Q8.9 19.885 6.95 17.867T5 13q0-2.571 1.615-5.029T11 3.79V5.3q0 1.275.878 2.138q.877.862 2.147.862q.47 0 .915-.159q.445-.158.84-.456l.432-.339q1.311.973 2.05 2.473T19 13h-1q0-.625-.125-1.213t-.35-1.15t-.562-1.062t-.763-.925q-.5.325-1.052.487q-.552.163-1.129.163q-1.555 0-2.697-1.025t-1.297-2.563q-1.95 1.63-2.988 3.522Q6 11.125 6 13q0 2.166 1.328 3.779t3.357 2.067");
}

</style>
