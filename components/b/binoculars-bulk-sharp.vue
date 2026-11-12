<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t75fmlzqd"/><path class="vu65r37xo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:binoculars-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.t75fmlzqd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 8V6a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v10a4 4 0 0 1-8 0c0-1.036.374-2.037.865-2.935c.642-1.177 1.493-2.216 2.258-3.312C5.413 9.337 6 8.49 6 8m8 8V6a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v2c0 .49.587 1.337.877 1.753c.765 1.096 1.616 2.135 2.258 3.312c.491.898.865 1.899.865 2.935a4 4 0 0 1-8 0");
}

.vu65r37xo {
  d: path("M15 10a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2ZM2.315 14.443a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114m12 0a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114M4.157 16.778a2 2 0 1 0 3.686-1.556a2 2 0 0 0-3.686 1.556m12 0a2 2 0 1 0 3.686-1.556a2 2 0 0 0-3.686 1.556");
}

</style>
