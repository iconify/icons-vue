<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z8_mfybfs"/><path class="m6jgykb-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crew-on-site" /></template>
<style>
.m6jgykb-n {
  d: path("M3.5 19a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm8.065-6.288q-.134.123-.239.271q-.106.148-.179.314q-.072.166-.11.344Q17 13.818 17 14q0 .086.008.172t.026.169q.016.085.041.167t.058.162q.033.079.074.155t.088.147t.102.138t.116.127q.06.061.127.116q.066.054.138.102q.071.048.147.088q.076.041.155.074q.08.033.162.058t.167.041q.084.017.169.026t.172.008q.086 0 .172-.008t.169-.026q.085-.016.167-.041t.162-.058t.155-.074t.147-.088q.072-.048.138-.102q.067-.055.127-.116q.061-.06.116-.127q.054-.066.102-.138q.048-.071.088-.147q.041-.076.074-.155q.033-.08.058-.162t.041-.167t.026-.169q.008-.086.008-.172q0-.116-.015-.231q-.016-.115-.046-.227q-.031-.112-.075-.219q-.045-.108-.104-.208t-.13-.191t-.155-.173q-.082-.082-.175-.151q-.093-.07-.195-.127M16 21.5a2.75 2.75 0 0 1 5.5 0M18.5 9l-2-3a2.5 2.5 0 1 1 4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z8_mfybfs {
  d: path("M2.5 17.5V11A1.5 1.5 0 0 1 4 9.5h5V12h2l2 2.5v3Z");
}

</style>
