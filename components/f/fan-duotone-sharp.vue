<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="icy59bcqe"/><path class="ymsc_qbxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fan-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.icy59bcqe {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8.753 11.404c-1.438-.701-1.78-1.591-2.46-3.683a3 3 0 1 1 5.706-1.854c.425 1.308.096 1.979-.252 2.688c-.232.474-.43.926-.486 1.459a2.5 2.5 0 0 1 1.812 1.088c1.326-.895 2.268-.746 4.42-.289a3 3 0 0 1-1.248 5.869c-2.152-.457-1.928-1.772-3.222-2.713a2.5 2.5 0 0 1-1.849 1.025c.112 1.596-.487 2.337-1.959 3.972a3 3 0 1 1-4.459-4.015c.92-1.022 1.666-1.072 2.454-1.125c.527-.036 1.017-.092 1.506-.309a2.5 2.5 0 0 1 .037-2.113");
}

.ymsc_qbxr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.753 11.404c-1.438-.701-1.78-1.591-2.46-3.683a3 3 0 1 1 5.706-1.854c.68 2.092-.57 2.555-.738 4.147m1.812 1.088c1.326-.895 2.268-.746 4.42-.289a3 3 0 1 1-1.248 5.869c-2.152-.457-1.928-1.772-3.222-2.713m-1.849 1.025c.112 1.596-.487 2.337-1.96 3.972a3 3 0 1 1-4.458-4.015c1.472-1.634 2.498-.783 3.96-1.434M8.5 12.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 0 0-5 0");
}

</style>
