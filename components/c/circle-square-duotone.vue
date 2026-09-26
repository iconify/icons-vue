<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pys0i3bjn"/><path class="r8di_ca7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-square-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.pys0i3bjn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 9C17 13.4183 13.4183 17 9 17C4.5817 17 1 13.4183 1 9C1 4.5817 4.5817 1 9 1C13.4183 1 17 4.5817 17 9Z");
}

.r8di_ca7a {
  d: path("M11 8H20C21.6569 8 23 9.3431 23 11V20C23 21.6569 21.6569 23 20 23H11C9.3431 23 8 21.6569 8 20V11C8 9.3431 9.3431 8 11 8Z");
}

</style>
