<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pp163p-pb"/><path class="urw-zobvg"/><path class="mh0lanbpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:auto" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mh0lanbpe {
  fill: var(--svg-color--000, #000);
  d: path("m19.58 14.94l-3.316-2.074v-1.783l1.421.757V8.57l-4.737-3.08v6.982l-1.415.807l6.723 4.023L12 21l-7.58-4.48V7.56L12 3l7.58 4.56zM6.315 8.571v5.83l4.736-2.88V5.61zm3.469 5.71l-2.798 1.727L12 18.97l2.832-1.675z");
}

.pp163p-pb {
  fill: var(--svg-color--e9595c, #e9595c);
  d: path("m6.73 15.965l3.023-1.894l5.376 3.197l-3.01 1.934z");
}

.urw-zobvg {
  fill: var(--svg-color--109e92, #109e92);
  d: path("M11.166 5.366L5.958 8.523v6.094l5.209-3.03z");
}

</style>
