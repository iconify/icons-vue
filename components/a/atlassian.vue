<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGH6PerbeJ" x1="99.687%" x2="39.836%" y1="15.801%" y2="97.438%"><stop offset="0%" class="sav6x4bmf"/><stop offset="92.3%" class="g_gp7lgqe"/></linearGradient></defs><path fill="url(#SVGH6PerbeJ)" class="oov-tlbbh"/><path class="lyr7lvbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:atlassian" /></template>
<style>
.g_gp7lgqe {
  stop-color: var(--svg-color--2684ff, #2684ff);
}

.lyr7lvbel {
  fill: var(--svg-color--2681ff, #2681ff);
  d: path("M121.756 4.011c-35.033 55.505-32.721 116.979-9.646 163.13l42.06 84.121a7.49 7.49 0 0 0 6.697 4.14h87.227a7.488 7.488 0 0 0 6.697-10.838S137.445 9.837 134.493 3.964c-2.64-5.258-9.344-5.33-12.737.047");
}

.oov-tlbbh {
  d: path("M75.793 117.95c-3.82-4.08-9.77-3.85-12.367 1.342L.791 244.565a7.488 7.488 0 0 0 6.697 10.838h87.228a7.22 7.22 0 0 0 6.699-4.14c18.808-38.89 7.413-98.018-25.622-133.314");
}

.sav6x4bmf {
  stop-color: var(--svg-color--0052cc, #0052cc);
}

</style>
