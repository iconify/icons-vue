<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="sgzthjbcg"/><path class="xs_nsnm1g"/><path class="awd8nn3nn"/><path class="mrbjqib8m"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:knc-background" /></template>
<style>
.awd8nn3nn {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.914 4.34a.235.235 0 0 1 .372.233L9.86 11.799a.2.2 0 0 0 0 .089l1.432 7.573a.23.23 0 0 1-.102.24a.24.24 0 0 1-.26-.002l-4.473-2.974a.23.23 0 0 1-.104-.195V7.87a.23.23 0 0 1 .094-.187z");
}

.ft5dv1b6b {
  fill: none;
}

.mrbjqib8m {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.316 19.809a.236.236 0 0 0 .362.151l4.422-2.94a.234.234 0 0 0-.006-.394l-5.645-3.529a.235.235 0 0 0-.356.243zm4.97-4.17a.24.24 0 0 0 .24.007a.24.24 0 0 0 .121-.205V8.676a.234.234 0 0 0-.233-.234a.23.23 0 0 0-.117.03l-5.701 3.201a.24.24 0 0 0-.12.2a.23.23 0 0 0 .11.204z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sgzthjbcg {
  fill: var(--svg-color--31cb9e, #31cb9e);
  d: path("M24 0H0v24h24z");
}

.xs_nsnm1g {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.694 4.047a.235.235 0 0 0-.372.142l-1.233 6.248a.235.235 0 0 0 .346.25l5.475-3.075a.233.233 0 0 0 .098-.302a.23.23 0 0 0-.073-.09z");
}

</style>
