<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq-oi9oqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:combustion-triangle" /></template>
<style>
.fq-oi9oqc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m20.146 15.196l-5.218-9.099Q13.955 4.401 12 4.401T9.072 6.097l-5.218 9.099q-.967 1.687.008 3.371t2.92 1.683h10.436q1.945 0 2.92-1.683t.008-3.371m-6.652-6.789q.09.718.928 1.98Q15.75 12.389 15.75 14q0 .208-.107.386q-1.239 2.061-3.643 2.061t-3.643-2.061Q8.25 14.208 8.25 14q0-2.707 2.263-3.462q.064-.021.131-.031t.135-.006q.068.002.134.017t.129.041t.119.064t.106.084t.089.101t.069.116q.067-.211.142-.435Q12 9.202 12 8.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.068 0 .135.012t.13.037q.064.024.122.059t.109.08t.093.098t.074.114t.052.125q.021.065.029.132");
}

</style>
