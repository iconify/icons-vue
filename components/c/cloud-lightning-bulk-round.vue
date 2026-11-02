<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u0k3xpq5f"/><path class="rc1di5bac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-lightning-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rc1di5bac {
  d: path("M12.414 17H14a1.002 1.002 0 0 1 .707 1.707l-3 3a.999.999 0 1 1-1.414-1.414L11.586 19H10a1.002 1.002 0 0 1-.707-1.707l3-3a.999.999 0 1 1 1.414 1.414Z");
}

.u0k3xpq5f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 16a5 5 0 0 1-4.987-4.646a5 5 0 0 1 4.282-5.305a6.58 6.58 0 0 1 2.773-3.121a6.75 6.75 0 0 1 4.33-.792c2.381.358 4.323 1.911 5.151 4.18c.21.58.346 1.184.407 1.799A4 4 0 0 1 18 16Z");
}

</style>
