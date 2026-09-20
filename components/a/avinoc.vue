<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1mjunbsu"><path class="dnnn5h5pq"/><path class="k3j_vhiyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:avinoc" /></template>
<style>
.dnnn5h5pq {
  d: path("M7.373 4.059h7.2L11.74 5.647H8.4L4.8 12l3.6 6.353h7.2L18.94 12L17.4 9.353l.26-3.177L21 12l-4.373 7.941H7.373L3 12z");
}

.k3j_vhiyn {
  d: path("m7.373 10.412l9.513-6.353L15.6 15.176l-2.573-4.764z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

</style>
