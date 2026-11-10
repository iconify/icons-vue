<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c9bekhy_r"/><path class="ixjr0wb5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-left-to-line-sharp-duotone" /></template>
<style>
.c9bekhy_r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.475 3.992L13.876 5.419L8.408 10.794L8.199 11H23V13H8.199L8.408 13.206L13.876 18.581L12.475 20.007L5.054 12.713C4.863 12.525 4.754 12.268 4.754 12C4.754 11.732 4.863 11.475 5.054 11.287L12.475 3.992ZM3 4V20H1V4H3Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ixjr0wb5l {
  d: path("M12.476 3.992L13.877 5.419L8.409 10.794L8.2 11H23.001V13H8.2L8.409 13.206L13.877 18.581L12.476 20.007L5.055 12.713C4.889 12.55 4.774 12.229 4.75 11.998C4.773 11.767 4.888 11.452 5.055 11.287L12.476 3.992Z");
}

</style>
