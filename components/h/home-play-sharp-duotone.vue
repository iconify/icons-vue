<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ql-coxber"/><path class="j8zt16-tp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-play-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j8zt16-tp {
  d: path("M9.087 8.36C9.384 8.25 9.784 8.27 10.052 8.44L16.428 12.66C16.707 12.85 16.876 13.23 16.876 13.56C16.84 13.85 16.672 14.17 16.428 14.33L10.052 18.55C9.745 18.76 9.35 18.77 9.026 18.6C8.703 18.43 8.501 18.09 8.5 17.72V9.28C8.5 8.91 8.763 8.54 9.087 8.36Z");
}

.ql-coxber {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.389 2.2C11.749 1.93 12.251 1.93 12.611 2.2L21.611 9.15C21.856 9.34 22 9.64 22 9.95V21.05C21.948 21.56 21.517 22 21 22H3C2.483 22 2.052 21.56 2 21.05V9.95C2 9.64 2.144 9.34 2.389 9.15L11.389 2.2Z");
}

</style>
