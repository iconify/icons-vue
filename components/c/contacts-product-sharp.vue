<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf-hshb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contacts-product-sharp" /></template>
<style>
.nf-hshb2w {
  fill: currentColor;
  d: path("M5.76 20.462q-.35 0-.613-.277q-.264-.277-.264-.62v-2.223q0-1.906 1.184-3.367q1.185-1.461 3.046-1.864q-.853.6-1.322 1.511t-.47 1.942v3.997q0 .232.075.463q.075.232.212.437zm3.108 0q-.359 0-.623-.267t-.264-.63v-4q0-1.5 1.035-2.532Q10.052 12 11.552 12h4.01q1.484 0 2.517 1.033t1.032 2.533v1.33q0 1.5-1.032 2.533t-2.533 1.033zM12 10.208q-1.393 0-2.364-.967q-.97-.968-.97-2.368t.97-2.367T12 3.538t2.364.968t.97 2.367t-.97 2.367t-2.364.968");
}

</style>
