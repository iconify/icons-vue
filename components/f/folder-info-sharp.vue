<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqdn1m71t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-info-sharp" /></template>
<style>
.oqdn1m71t {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2H21v5.029q-.846-.685-1.867-1.03t-2.1-.345q-2.67 0-4.534 1.864t-1.865 4.534q0 .512.07.992t.246.956zm11.165.836Q13 18.67 13 17t1.165-2.835T17 13t2.836 1.165T21 17t-1.164 2.836T17 21t-2.835-1.164m2.45-.297h.77V16.46h-.77zm.735-4.227q.15-.15.15-.35t-.15-.35t-.35-.15t-.35.15t-.15.35t.15.35t.35.15t.35-.15");
}

</style>
