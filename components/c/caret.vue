<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6gx1lprw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:caret" /></template>
<style>
.e6gx1lprw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.317 17.19l5-11q.031-.068.074-.128t.097-.11t.117-.089q.062-.039.132-.065q.069-.026.142-.038t.146-.01t.146.02t.139.047q.124.057.22.153t.153.22l5 11q.03.067.047.139t.02.146q.002.073-.01.146t-.038.142t-.065.132t-.089.117t-.11.097t-.128.074t-.139.047t-.146.02q-.073.002-.146-.01t-.142-.038t-.132-.065t-.117-.089t-.097-.11t-.074-.128L12 8.312L7.683 17.81q-.062.136-.171.238t-.249.154t-.288.048q-.15-.005-.285-.067q-.068-.031-.128-.074t-.11-.097t-.089-.117t-.065-.132t-.038-.142t-.01-.146q.003-.074.02-.146t.047-.139");
}

</style>
