<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p_jw6j-jz"/><path class="g3apbobdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cup-soda-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g3apbobdy {
  d: path("M17 5C17.315 5 17.611 5.15 17.8 5.4L19.6 7.8C19.859 8.15 20 8.57 20 9C20 10.1 19.105 11 18 11H6C4.895 11 4 10.1 4 9C4 8.57 4.141 8.15 4.4 7.8L6.239 5.35C6.426 5.15 6.725 5 7 5H17Z");
}

.p_jw6j-jz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 9C20 9.81 19.517 10.5 18.825 10.82L15.97 22.24C15.858 22.69 15.459 23 15 23H9C8.541 23 8.142 22.69 8.03 22.24L5.174 10.82C4.482 10.5 4 9.81 4 9C4 8.57 4.141 8.15 4.4 7.8L6.239 5.35C6.426 5.15 6.725 5 7 5H10.382L12.138 1.49C12.323 1.22 12.669 1 13 1H17V3H13.618L12.618 5H17C17.315 5 17.611 5.15 17.8 5.4L19.6 7.8C19.859 8.15 20 8.57 20 9Z");
}

</style>
