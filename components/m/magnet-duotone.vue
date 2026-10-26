<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="irc4d0bsv"/><path clip-rule="evenodd" class="ufp00xusf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:magnet-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.irc4d0bsv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 13L3 4C3 2.8954 3.8954 2 5 2L8 2C9.1046 2 10 2.8954 10 4L10 13C10 14.1046 10.8954 15 12 15C13.1046 15 14 14.1046 14 13L14 4C14 2.8954 14.8954 2 16 2L19 2C20.1046 2 21 2.8954 21 4L21 13C21.001 16.3261 19.1673 19.3814 16.2316 20.9449C14.9281 21.6383 13.4743 22.001 11.9978 22.001C11.2516 22.001 10.5082 21.9083 9.7847 21.7251C6.5867 20.9105 4.0895 18.4133 3.2749 15.2153C3.0919 14.4911 2.9995 13.747 3 13Z");
}

.ufp00xusf {
  fill-rule: evenodd;
  d: path("M3 8L3 4C3 2.8954 3.8954 2 5 2L8 2C9.1046 2 10 2.8954 10 4L10 8L3 8ZM14 8L14 4C14 2.8954 14.8954 2 16 2L19 2C20.1046 2 21 2.8954 21 4L21 8L14 8Z");
}

</style>
