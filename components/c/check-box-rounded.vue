<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mno7ulmjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:check-box-rounded" /></template>
<style>
.mno7ulmjo {
  fill: currentColor;
  d: path("m10.6 14.092l-2.496-2.496q-.14-.14-.344-.15t-.364.15t-.16.354t.16.354l2.639 2.638q.242.243.565.243t.566-.243l5.476-5.476q.14-.141.15-.345t-.15-.363t-.353-.16t-.355.16zM5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
