<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_z8166-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lock-clock" /></template>
<style>
.s_z8166-h {
  fill: currentColor;
  d: path("M9 9h6V7q0-1.25-.875-2.125T12 4t-2.125.875T9 7zm5.78 11.451q-1.164-1.164-1.164-2.835t1.164-2.836t2.836-1.164q1.67 0 2.835 1.164t1.165 2.836q0 1.67-1.165 2.835t-2.835 1.165q-1.672 0-2.836-1.165m4.486-.64l.546-.545L18 17.454V14.73h-.77v3.046zM12.673 21H6.616q-.672 0-1.144-.472T5 19.385v-8.77q0-.67.472-1.143Q5.944 9 6.616 9H8V7q0-1.671 1.165-2.835Q10.329 3 12 3t2.836 1.165T16 7v2h1.385q.67 0 1.143.472q.472.472.472 1.144V11.8q-.346-.136-.692-.151q-.347-.014-.712-.014q-2.483 0-4.232 1.749t-1.749 4.232q0 .92.261 1.789T12.673 21");
}

</style>
