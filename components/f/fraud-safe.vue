<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nk-webg6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fraud-safe" /></template>
<style>
.nk-webg6z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.758 4.796l-7.5-2.75Q12.133 2 12 2t-.258.046l-7.5 2.75q-.108.04-.2.11q-.091.07-.157.165q-.066.094-.1.204q-.035.11-.035.225v6q0 7.276 7.973 10.447q.133.053.277.053t.277-.053Q20.25 18.776 20.25 11.5v-6q0-.115-.035-.225q-.034-.11-.1-.204q-.066-.095-.157-.165q-.092-.07-.2-.11m-8.787 8.615l3.972-4.413q.049-.055.108-.099t.126-.076t.138-.05t.146-.022q.073-.004.146.007q.074.01.143.035q.07.025.133.062q.064.038.119.088q.111.099.175.234t.072.284t-.042.289q-.05.141-.15.252l-4.5 5l-.027.028q-.105.106-.243.163T11 15.25t-.287-.057t-.243-.163l-2.5-2.5q-.106-.105-.163-.243T7.75 12t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
