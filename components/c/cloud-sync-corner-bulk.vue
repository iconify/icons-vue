<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cvy-xbymr"/><path class="lj_kdlfqy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-sync-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cvy-xbymr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 20a6 6 0 0 1-.74-11.955c.742-2.012 2.206-3.704 4.274-4.403c2.856-.964 5.823.266 7.337 2.833c.419.717.721 1.496.896 2.307A.998.998 0 0 1 17.791 10H10a.997.997 0 0 0-1 1v8a1 1 0 0 1-1 1Z");
}

.lj_kdlfqy {
  d: path("M15 12a1 1 0 0 1 1 1v3a1 1 0 0 1-2 0v-.748a3.475 3.475 0 0 0 1.447 4.854a1 1 0 1 1-.894 1.788a5.4 5.4 0 0 1-1.422-1.025a5.4 5.4 0 0 1-1.025-1.422A5.46 5.46 0 0 1 12.423 14H12a1 1 0 0 1 0-2Zm6.577 8H22a1 1 0 0 1 0 2h-3a.997.997 0 0 1-1-1v-3a1 1 0 0 1 2 0v.748a3.475 3.475 0 0 0-1.447-4.854a.999.999 0 1 1 .894-1.788a5.4 5.4 0 0 1 1.422 1.025c.417.415.763.895 1.025 1.422A5.46 5.46 0 0 1 21.577 20");
}

</style>
