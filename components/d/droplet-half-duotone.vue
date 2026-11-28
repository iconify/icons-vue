<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mjjvx_bvq"/><path class="bnfkyc32o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:droplet-half-duotone" /></template>
<style>
.bnfkyc32o {
  d: path("M12 7C12 6.4477 12.4477 6 13 6C13.3148 6 13.6111 6.1482 13.8 6.4L16.8 10.4C17.5789 11.4386 18 12.7018 18 14C18 16.8512 15.9935 19.3085 13.2 19.8788C13.1342 19.8922 13.0672 19.899 13 19.899C12.4477 19.899 12 19.4513 12 18.899Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.mjjvx_bvq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.4 9.2C19.4386 10.5848 20 12.269 20 14C20 18.4183 16.4183 22 12 22C7.5817 22 4 18.4183 4 14C4 12.269 4.5614 10.5848 5.6 9.2L10.4 2.8C10.7777 2.2965 11.3703 2 12 2C12.6297 2 13.2223 2.2965 13.5999 2.7999L18.4 9.2Z");
}

</style>
