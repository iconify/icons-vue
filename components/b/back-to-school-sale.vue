<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mehqnddav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:back-to-school-sale" /></template>
<style>
.mehqnddav {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.779 14.971l-4.521 4.521q-.258.258-.606.369l-2.402.764q-.097.031-.198.048t-.203.021t-.203-.007t-.201-.034t-.195-.062q-.095-.037-.184-.087q-.089-.051-.17-.112t-.154-.134t-.134-.154t-.112-.17q-.05-.089-.087-.184q-.038-.095-.062-.195q-.024-.099-.034-.201q-.011-.101-.007-.203t.021-.203t.048-.198l.764-2.402q.111-.348.369-.606L15.439 4.811q.052-.052.109-.099t.118-.088t.127-.075q.065-.035.133-.063q.068-.029.138-.05t.143-.036t.146-.021q.073-.008.147-.008t.147.008t.146.021q.072.015.143.036t.138.05q.068.028.133.063q.065.034.127.075q.061.041.118.088t.109.099l1.628 1.628q.052.052.099.109t.088.118q.041.062.075.127q.035.065.063.133q.029.068.05.138t.036.143q.014.073.021.146t.008.147t-.008.147q-.007.073-.021.146q-.015.072-.036.143t-.05.138q-.028.068-.063.133q-.034.065-.075.127q-.041.061-.088.118t-.099.109l-4.218 4.218M4.25 16L8 19.75m6-13.5L17.75 10m-3 11.25l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
