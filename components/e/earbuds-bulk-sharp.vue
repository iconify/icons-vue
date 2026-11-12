<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="w-otu3bfi"/><path class="f-w-a3bdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:earbuds-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f-w-a3bdr {
  d: path("M6.01 6a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm12 0a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2Z");
}

.w-otu3bfi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 7v13c0 .571-.286 1.08-.758 1.395c-.924.615-2.433.443-3.02-.563A1.65 1.65 0 0 1 7 20v-9H6c-1.079 0-2.172-.259-2.957-1.043C2.259 9.172 2 8.079 2 7s.259-2.172 1.043-2.957C3.828 3.259 4.921 3 6 3c1.706 0 3.617.636 4.52 2.184c.322.551.48 1.179.48 1.816m7 4h-1v9c0 .292-.075.579-.222.832c-.587 1.006-2.096 1.178-3.02.563A1.67 1.67 0 0 1 13 20V7c0-.637.158-1.265.48-1.816C14.383 3.636 16.294 3 18 3c1.079 0 2.172.259 2.957 1.043C21.741 4.828 22 5.921 22 7s-.259 2.172-1.043 2.957C20.172 10.741 19.079 11 18 11");
}

</style>
