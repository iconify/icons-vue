<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmem2tnob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-info-outline-sharp" /></template>
<style>
.nmem2tnob {
  fill: currentColor;
  d: path("M4 18V6v5.373v-.72zm6.95 1H3V5h6.596l2 2H21v5.029q-.233-.2-.473-.358T20 11.373V8h-8.806l-2-2H4v12h6.69q.037.275.103.516q.067.24.157.484m8.886-4.835Q21 15.329 21 17t-1.164 2.836T17 21t-2.835-1.164T13 17t1.165-2.835T17 13t2.836 1.165m-3.22 5.374h.768V16.46h-.769zm.734-4.227q.15-.15.15-.35t-.15-.35t-.35-.15t-.35.15t-.15.35t.15.35t.35.15t.35-.15");
}

</style>
