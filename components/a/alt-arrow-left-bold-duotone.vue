<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctf7tpbxx"/><path class="i_23a8b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-left-bold-duotone" /></template>
<style>
.ctf7tpbxx {
  fill: currentColor;
  d: path("M11.5956 8.30273L8.16485 11.6296C7.94505 11.8428 7.94505 12.1573 8.16485 12.3704L14.7953 18.8001C15.2091 19.2013 16 18.9581 16 18.4297V12.7071L11.5956 8.30273Z");
}

.i_23a8b0l {
  fill: currentColor;
  d: path("M16 11.2929L16 5.5703C16 5.04189 15.2091 4.79869 14.7953 5.1999L12.3136 7.60648L16 11.2929Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
