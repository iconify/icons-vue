<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7ynj4xpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:direct-message" /></template>
<style>
.j7ynj4xpj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.97 2.97l-10 10q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l10-10q.106-.105.163-.244l-6.999 17q-.057.136-.16.241t-.239.162q-.067.029-.14.045q-.072.015-.146.016t-.146-.013t-.142-.041q-.068-.027-.13-.067t-.115-.092t-.094-.113t-.071-.129l-2.882-6.724l-6.724-2.882q-.136-.058-.239-.162t-.16-.241q-.056-.138-.056-.288t.058-.286q.057-.138.163-.243q.105-.106.243-.163l17-6.999q-.138.057-.244.163");
}

</style>
