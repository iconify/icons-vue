<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia39kttwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-triangle" /></template>
<style>
.ia39kttwv {
  fill: currentColor;
  d: path("M2.02 19L12 2l10 17zm9.48-3.404h1v-1.942h1.98v-1H12.5V10.73h-1v1.923H9.539v1H11.5z");
}

</style>
