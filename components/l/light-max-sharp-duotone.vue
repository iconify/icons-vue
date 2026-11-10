<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vdou-vbak"/><path clip-rule="evenodd" class="wqf7x0b3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:light-max-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.vdou-vbak {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 15V17H7V15H17Z");
}

.wqf7x0b3q {
  fill-rule: evenodd;
  d: path("M7.414 11L6 12.41L4 10.41L5.414 9L7.414 11ZM20.071 10.41L18.071 12.41L16.657 11L18.657 9L20.071 10.41ZM5 15V17H1V15H5ZM23 15V17H19V15H23ZM13 7V11H11V7H13Z");
}

</style>
