<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr9jmhbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:carry-on-bag-sharp" /></template>
<style>
.qr9jmhbjt {
  fill: currentColor;
  d: path("M14.938 21.063Q14.5 20.625 14.5 20t.438-1.062T16 18.5t1.063.438T17.5 20t-.437 1.063T16 21.5t-1.062-.437M6 21V7h3v14zm4.5 0V7H14V4h-2V2h4v15q-1.25 0-2.125.875T13 20q0 .275.038.513t.137.487z");
}

</style>
