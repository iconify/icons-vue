<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn5qsc9xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:amino-group" /></template>
<style>
.pn5qsc9xw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.581 4.581Q5.75 6.411 5.75 9t1.831 4.419q.065.066.131.128l-.792.905q-.609-.202-1.42-.202q-3.25 0-3.25 3.25t3.25 3.25t3.25-3.25q0-1.388-.593-2.183l.756-.864q1.378.797 3.087.797t3.087-.797l.756.864q-.593.795-.593 2.183q0 3.25 3.25 3.25q1.346 0 2.298-.952t.952-2.298t-.952-2.298t-2.298-.952q-.811 0-1.42.202l-.792-.905q.066-.062.131-.128Q18.25 11.589 18.25 9t-1.831-4.419Q14.589 2.75 12 2.75T7.581 4.581");
}

</style>
