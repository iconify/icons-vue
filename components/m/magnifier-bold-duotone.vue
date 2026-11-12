<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="cl66i7bqg"/><path class="anq4ponik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifier-bold-duotone" /></template>
<style>
.anq4ponik {
  fill: currentColor;
  d: path("M21.7891 20.7656C22.0713 21.0479 22.0711 21.5058 21.7891 21.7881C21.5068 22.0704 21.0489 22.0704 20.7666 21.7881L17.6855 18.707C18.0516 18.3926 18.3926 18.0506 18.707 17.6846L21.7891 20.7656Z");
}

.cl66i7bqg {
  cx: 11.5px;
  cy: 11.5px;
  r: 9.5px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
