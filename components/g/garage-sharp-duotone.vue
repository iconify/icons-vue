<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y2gaodogg"/><path clip-rule="evenodd" class="qvep18bol"/><path class="tksx2_b_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:garage-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qvep18bol {
  fill-rule: evenodd;
  d: path("M18 21H6V11H18V21ZM10 19H14V17H10V19Z");
}

.tksx2_b_o {
  d: path("M22.447 6.105C22.786 6.275 23 6.621 23 7V8H1V7C1 6.621 1.214 6.275 1.553 6.105L1.764 6H22.236L22.447 6.105Z");
}

.y2gaodogg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.66 1.06C11.916 0.967 12.201 0.982 12.447 1.105L22.447 6.105C22.786 6.275 23 6.621 23 7V22C23 22.552 22.552 23 22 23H2C1.448 23 1 22.552 1 22V7C1 6.621 1.214 6.275 1.553 6.105L11.553 1.105L11.66 1.06Z");
}

</style>
