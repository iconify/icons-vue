<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y9kbw7bwk"/><path class="r444_ybdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:key-sync-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.r444_ybdn {
  d: path("m12.293 3.293l1-1a.999.999 0 1 1 1.414 1.414L14.414 4l1.293 1.293a1 1 0 0 1-.845 1.697a1.001 1.001 0 0 1-1.698.846l-1.292-1.293l-3.165 3.164a.999.999 0 1 1-1.414-1.414ZM21 14a1 1 0 0 1-1 1h-3a1 1 0 0 1 0-2h.748a3.47 3.47 0 0 0-4.854 1.447a1 1 0 1 1-1.788-.894a5.4 5.4 0 0 1 1.025-1.422a5.4 5.4 0 0 1 1.422-1.025a5.46 5.46 0 0 1 5.447.317V11a1 1 0 0 1 2 0Zm-10 4a1 1 0 0 1 1-1h3a1 1 0 0 1 0 2h-.748a3.47 3.47 0 0 0 4.854-1.447a1 1 0 1 1 1.788.894a5.4 5.4 0 0 1-1.025 1.422a5.4 5.4 0 0 1-1.422 1.025A5.46 5.46 0 0 1 13 20.577V21a1 1 0 0 1-2 0Z");
}

.y9kbw7bwk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.707 8.293a3.83 3.83 0 1 1-5.416 5.416a3.83 3.83 0 0 1 5.416-5.416");
}

</style>
