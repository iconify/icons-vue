<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b72fuevhb"/><path class="dkzo2nc7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-ring-bulk" /></template>
<style>
.b72fuevhb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.171 20H7a3 3 0 0 1-3-3c0-.39.098-.773.299-1.108c.133-.222.312-.417.494-.599c.065-.066.145-.133.193-.214C5 15.057 5 15.026 5 15v-4a7 7 0 1 1 14 0v4c0 .026 0 .057.014.079c.048.081.128.148.193.214c.182.182.361.377.494.599c.201.335.299.718.299 1.108a3 3 0 0 1-3 3h-2.171a3 3 0 0 1-5.658 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.dkzo2nc7a {
  d: path("M3.152 5.47A10.3 10.3 0 0 1 6.47 2.152a1 1 0 0 1 1.06 1.696A8.34 8.34 0 0 0 4.848 6.53a1 1 0 0 1-1.696-1.06M17.53 2.152a10.3 10.3 0 0 1 3.318 3.318a1 1 0 0 1-1.696 1.06a8.34 8.34 0 0 0-2.682-2.682a1 1 0 0 1-.051-1.662c.33-.235.768-.248 1.111-.034M11 19a1 1 0 0 0 1.387.922A.99.99 0 0 0 13 19a1 1 0 0 1 2 0a3 3 0 0 1-6 0a1 1 0 0 1 2 0");
}

</style>
