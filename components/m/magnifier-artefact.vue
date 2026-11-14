<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5iq4bbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:magnifier-artefact" /></template>
<style>
.w5iq4bbog {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 8q0-2.589 1.831-4.419Q8.411 1.75 11 1.75t4.419 1.831T17.25 8q0 2.206-1.329 3.861l5.109 5.109q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-5.109-5.109Q13.206 14.25 11 14.25q-2.589 0-4.419-1.831Q4.75 10.589 4.75 8M2.467 19.721l.172-1.376q.176-1.407 1.521-1.855l3.014-1.005q.884-.295 1.718.122l2.33 1.165q1.671.836 1.157 2.631l-.347 1.215q-.466 1.632-2.163 1.632h-5.17q-1.015 0-1.687-.761q-.671-.761-.545-1.768");
}

</style>
