<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jz8kklmuy"/><path clip-rule="evenodd" class="tho_ewv3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-bullet-indent-sharp-two-tone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jz8kklmuy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 20H11V18H22V20Z");
}

.tho_ewv3y {
  fill-rule: evenodd;
  d: path("M20 13H9V11H20V13ZM18 6H7V4H18V6ZM7.5 17.5C8.328 17.5 9 18.17 9 19C9 19.83 8.328 20.5 7.5 20.5C6.672 20.5 6 19.83 6 19C6 18.17 6.672 17.5 7.5 17.5ZM5.5 10.5C6.328 10.5 7 11.17 7 12C7 12.83 6.328 13.5 5.5 13.5C4.672 13.5 4 12.83 4 12C4 11.17 4.672 10.5 5.5 10.5ZM3.5 3.5C4.328 3.5 5 4.17 5 5C5 5.83 4.328 6.5 3.5 6.5C2.672 6.5 2 5.83 2 5C2 4.17 2.672 3.5 3.5 3.5Z");
}

</style>
