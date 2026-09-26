<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pqvnf0ygp"/><path class="x7b-zkp6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:caret-down-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pqvnf0ygp {
  fill: currentColor;
  d: path("M11.544 17.7413L5.0727 6.78411C4.86742 6.43652 5.12126 6 5.52868 6H18.4713C18.8787 6 19.1326 6.43652 18.9273 6.7841L12.456 17.7413C12.2523 18.0862 11.7477 18.0862 11.544 17.7413Z");
  stroke: none;
}

.x7b-zkp6h {
  d: path("M11.544 17.7413L5.0727 6.78411C4.86742 6.43652 5.12126 6 5.52868 6H18.4713C18.8787 6 19.1326 6.43652 18.9273 6.7841L12.456 17.7413C12.2523 18.0862 11.7477 18.0862 11.544 17.7413Z");
}

</style>
