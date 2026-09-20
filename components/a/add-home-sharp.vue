<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk1nyvbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-home-sharp" /></template>
<style>
.qk1nyvbcq {
  fill: currentColor;
  d: path("M17.616 18.885h.769v-2.5h2.5v-.77h-2.5v-2.5h-.77v2.5h-2.5v.77h2.5zm-2.451-.05Q14 17.672 14 16t1.165-2.835T18 12t2.836 1.165T22 16t-1.164 2.836T18 20t-2.835-1.164M5 18V7.5l7-5.288L19 7.5v1.82q-.25-.045-.5-.067t-.5-.022q-2.828 0-4.799 1.97q-1.97 1.97-1.97 4.799q0 .512.085 1.012t.243.988z");
}

</style>
