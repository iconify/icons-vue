<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgp0r1nxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:consent-check" /></template>
<style>
.kgp0r1nxv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 2.75h-3q-3.21 0-5.48 2.27T2.75 10.5v3q0 3.21 2.27 5.48t5.48 2.27h3q3.21 0 5.48-2.27t2.27-5.48v-3q0-3.21-2.27-5.48T13.5 2.75m-3.042 11.647l5.473-6.385q.048-.056.106-.102t.124-.079t.137-.053t.144-.026t.147.003t.144.032t.135.059t.12.085q.113.097.181.23t.079.281t-.035.291t-.144.255l-6 7q-.018.022-.039.042q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094l-3-3q-.106-.105-.163-.243T6.75 12.5t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094z");
}

</style>
