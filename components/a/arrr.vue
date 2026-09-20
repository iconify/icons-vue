<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG36jIhbYH)" class="ua6musbjz"/><defs><linearGradient id="SVG36jIhbYH" x1="4.561" x2="19.553" y1="4.446" y2="20.457" gradientUnits="userSpaceOnUse"><stop class="gvrvndxaq"/><stop offset="1" class="jezxccrcr"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:arrr" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gvrvndxaq {
  stop-color: var(--svg-color--bf9b41, #bf9b41);
}

.jezxccrcr {
  stop-color: var(--svg-color--e2c97e, #e2c97e);
}

.ua6musbjz {
  d: path("M3.321 6.857A3.857 3.857 0 0 1 7.18 3h9.642c.913 0 1.749.321 2.411.849l-4.596 2.365H8.464A1.286 1.286 0 0 0 7.18 7.5v2.559l-3.86 1.993zm0 9.084V21h2.25a1.61 1.61 0 0 0 1.608-1.607V16.5h9.642a3.86 3.86 0 0 0 3.857-3.857v-5.65l-3.857 1.992V12a1.286 1.286 0 0 1-1.285 1.286H8.47z");
}

</style>
