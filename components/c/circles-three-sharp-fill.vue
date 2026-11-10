<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ufoqbsb6u"/><path class="xo754-w5x"/><path class="qyggjabdm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circles-three-sharp-fill" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qyggjabdm {
  d: path("M12 1C15.637 1 18.639 3.96 18.979 7.51C18.096 7.22 16.98 7 16 7C12.04 7 8.62 9.73 7.416 13.29C6.017 12.01 5 10.05 5 8C5 4.13 8.134 1 12 1Z");
}

.ufoqbsb6u {
  d: path("M3.416 10.71C4.012 12.47 5.197 14.16 6.663 15.24L7.016 15.49C7.009 15.64 7 15.85 7 16C7 18.59 8.095 20.92 9.845 22.56L10.003 22.71L9.793 22.76C9.221 22.92 8.62 23 8 23C4.134 23 1 19.87 1 16C1 13.95 2.016 11.99 3.416 10.71Z");
}

.xo754-w5x {
  d: path("M16 9C19.866 9 23 12.13 23 16C23 19.87 19.866 23 16 23C12.134 23 9 19.87 9 16C9 12.13 12.134 9 16 9Z");
}

</style>
