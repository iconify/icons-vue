<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cvy-xbymr"/><path class="r1ts84okl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-sync-corner-alt-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cvy-xbymr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 20a6 6 0 0 1-.74-11.955c.742-2.012 2.206-3.704 4.274-4.403c2.856-.964 5.823.266 7.337 2.833c.419.717.721 1.496.896 2.307A.998.998 0 0 1 17.791 10H10a.997.997 0 0 0-1 1v8a1 1 0 0 1-1 1Z");
}

.r1ts84okl {
  d: path("M20 12a1 1 0 0 1 2 0v3a1 1 0 0 1-.55.893l-.001.001h-.001A1 1 0 0 1 21 16h-3a1 1 0 0 1 0-2h.748a5 5 0 0 0-.195-.106l-.003-.001a3.473 3.473 0 0 0-4.656 1.554a1 1 0 1 1-1.788-.894a5.4 5.4 0 0 1 1.025-1.422a5.47 5.47 0 0 1 6.316-1.025l.003.001l.004.002q.282.141.546.314Zm-6 9.577V22a1 1 0 0 1-2 0v-3a1 1 0 0 1 .963-.999h.001L13 18h3a1 1 0 0 1 0 2h-.748a3.47 3.47 0 0 0 4.854-1.447a1 1 0 1 1 1.788.894A5.465 5.465 0 0 1 14 21.577");
}

</style>
