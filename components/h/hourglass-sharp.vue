<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_pn3p6ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hourglass-sharp" /></template>
<style>
.m_pn3p6ha {
  fill: currentColor;
  d: path("M4 22v-2h2v-3q0-1.525.713-2.863T8.7 12q-1.275-.8-1.987-2.137T6 7V4H4V2h16v2h-2v3q0 1.525-.712 2.863T15.3 12q1.275.8 1.988 2.138T18 17v3h2v2z");
}

</style>
