<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkrobmw2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:door-back-sharp" /></template>
<style>
.fkrobmw2a {
  fill: currentColor;
  d: path("M3 21v-2h2V3h14v16h2v2zm7.713-8.287Q11 12.425 11 12t-.288-.712T10 11t-.712.288T9 12t.288.713T10 13t.713-.288");
}

</style>
