<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oses70bfc"/><path class="pk5s7xkzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-minus-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.oses70bfc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 20a6 6 0 0 1-.74-11.955c.742-2.012 2.206-3.704 4.274-4.403c2.856-.964 5.823.266 7.337 2.833c.419.717.721 1.496.896 2.307A.998.998 0 0 1 17.791 10H9v9a1 1 0 0 1-1 1Z");
}

.pk5s7xkzd {
  d: path("M13 15h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2");
}

</style>
