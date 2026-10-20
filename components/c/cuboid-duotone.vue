<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m_rmc3mcf"/><path class="q_ayb7btx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cuboid-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m_rmc3mcf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.2929 7.2929L7 2.5858C7.3751 2.2107 7.8838 2 8.4142 2L21 2C21.5523 2 22 2.4477 22 3L22 15.5858C22 16.1162 21.7893 16.6249 21.4142 17L16.7071 21.7071C16.5196 21.8946 16.2652 22 16 22L4 22C2.8954 22 2 21.1046 2 20L2 8C2 7.7348 2.1054 7.4804 2.2929 7.2929Z");
}

.q_ayb7btx {
  d: path("M2 9L2 8C2 7.7348 2.1054 7.4804 2.2929 7.2929L7 2.5858C7.3751 2.2107 7.8838 2 8.4142 2L21 2C21.5523 2 22 2.4477 22 3L22 3.4142L16.7071 8.7071C16.5196 8.8946 16.2652 9 16 9L2 9Z");
}

</style>
