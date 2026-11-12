<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4fzscdmy"/><path class="fjjhjc8fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-down-bold-duotone" /></template>
<style>
.fjjhjc8fm {
  fill: currentColor;
  d: path("M11.2929 8H5.5703C5.04189 8 4.79869 8.79094 5.1999 9.20467L7.60648 11.6864L11.2929 8Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.j4fzscdmy {
  fill: currentColor;
  d: path("M8.30273 12.4044L11.6296 15.8351C11.8428 16.0549 12.1573 16.0549 12.3704 15.8351L18.8001 9.20467C19.2013 8.79094 18.9581 8 18.4297 8H12.7071L8.30273 12.4044Z");
}

</style>
