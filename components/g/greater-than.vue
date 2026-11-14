<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d07s4cbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:greater-than" /></template>
<style>
.d07s4cbri {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.409 4.871l10 6.5q.125.081.209.204q.085.123.116.269t.003.293t-.108.272q-.087.133-.22.22l-10 6.5q-.062.04-.131.067q-.068.028-.141.041t-.147.013q-.073-.001-.146-.016q-.072-.016-.14-.045t-.129-.071t-.112-.094t-.092-.115q-.081-.125-.108-.272q-.028-.147.003-.293t.116-.269q.084-.123.209-.204L15.624 12L6.591 6.129q-.062-.04-.115-.092q-.052-.052-.094-.112t-.071-.129t-.045-.14q-.015-.073-.016-.146q-.001-.074.013-.147t.041-.141t.067-.131t.092-.115t.112-.094t.129-.071t.14-.045q.073-.015.146-.016q.074-.001.147.013t.141.041t.131.067");
}

</style>
