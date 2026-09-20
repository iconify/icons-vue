<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ampc89k5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:article-shortcut-sharp" /></template>
<style>
.ampc89k5x {
  fill: currentColor;
  d: path("M6.625 22q-1.975 0-3.363-1.388T1.875 17.25q0-1.425.738-2.55T4.55 13H2v-2h6v6H6v-2.425q-.925.2-1.525.95t-.6 1.725q0 1.15.812 1.95t1.938.8zM7 9h10V7H7zm3 12v-4h4v-2h-4v-2h7v-2h-7V9H3V3h18v18z");
}

</style>
