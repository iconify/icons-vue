<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa3_n-b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fire-check-rounded" /></template>
<style>
.qa3_n-b6x {
  fill: currentColor;
  d: path("m16.235 19.598l3.704-3.704q.146-.146.344-.153t.363.159q.16.165.16.354t-.16.354l-3.84 3.826q-.243.243-.566.243t-.565-.242l-1.823-1.804q-.16-.14-.16-.345q0-.203.16-.363t.354-.16t.354.16zm-4.308-3.6q-.65.612-.894 1.517t.21 1.739q.105.18.22.336q.116.156.272.312l.098.092q-1.287-.015-2.41-.48q-1.123-.466-2.034-1.255q-1.114-.97-1.751-2.325Q5 14.581 5 13q0-2.273 1.274-4.471t3.51-3.912q.377-.292.797-.077q.419.216.419.708q0 1.265.883 2.159t2.142.893q.489 0 .927-.161t.829-.454q.2-.154.432-.146t.425.163q1.106.989 1.719 2.364q.612 1.376.626 2.884q.011.254-.094.495q-.106.241-.298.434l-2.356 2.356l-.006-.006q-1.127-1.127-2.314-1.05t-1.988.819");
}

</style>
