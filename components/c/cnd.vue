<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="spzqy-zum"/><path class="ci5--jakz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cnd" /></template>
<style>
.ci5--jakz {
  fill: var(--svg-color--0c0e15, #0c0e15);
  d: path("M12 13.125a1.125 1.125 0 1 0 0-2.25a1.125 1.125 0 0 0 0 2.25");
}

.ft5dv1b6b {
  fill: none;
}

.spzqy-zum {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M12 19.875a7.875 7.875 0 1 0 0-15.75a7.875 7.875 0 0 0 0 15.75M12 21a9 9 0 0 0 9-9a9 9 0 0 0-9-9a9 9 0 0 0-9 9a9 9 0 0 0 9 9");
}

</style>
