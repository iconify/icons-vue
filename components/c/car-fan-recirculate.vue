<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbtydblbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:car-fan-recirculate" /></template>
<style>
.zbtydblbq {
  fill: currentColor;
  d: path("M6.75 19q-.89 0-1.606-.518q-.715-.518-1.121-1.328H1v-4.942q0-.69.463-1.153t1.152-.463h1.116l1.538-4.155q.167-.427.545-.684T6.65 5.5h7.123q.39 0 .718.195t.546.51l.772 1.266l-1.878 2.202h-1.517L10 7.26L5.26 12L10 16.74l2.414-2.413h3.65l3.463-4.056l1.898.156q.69.056 1.133.539q.442.482.442 1.173v5.015h-3.042q-.387.81-1.102 1.328T17.25 19t-1.606-.518t-1.121-1.328H9.458q-.387.81-1.102 1.328T6.75 19M10 14.058l.627-.608l-1.002-1.008h5.566l5.936-6.923l-.663-.577l-5.68 6.616H9.626l1.002-1.008L10 9.942L7.942 12z");
}

</style>
