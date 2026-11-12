<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lpx3okbfr"/><path class="y_snzsi1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hearing-aid-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lpx3okbfr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 11.829V12a1 1 0 0 1-.553.894l-2 1a1 1 0 1 1-.894-1.788l.978-.489a3.001 3.001 0 1 1 2.469.212m-.293-3.536a.999.999 0 1 0-1.414 1.414a.999.999 0 1 0 1.414-1.414");
}

.y_snzsi1t {
  d: path("M3.708 7.496A9 9 0 0 1 13.789 2.18A8.994 8.994 0 0 1 21 11c-.001 1.483-.584 2.686-1.798 3.55c-.965.686-2.122 1.038-3.241 1.384c-.438.136-.879.27-1.309.432a5 5 0 0 0-.977.47c-.442.29-.675.624-.675 1.164a3.994 3.994 0 0 1-4 4a3.98 3.98 0 0 1-2.828-1.172A3.98 3.98 0 0 1 5 18a1 1 0 0 1 2 0a2 2 0 1 0 4 0c.001-1.23.559-2.168 1.579-2.837c.844-.553 1.836-.844 2.792-1.14c.502-.155 1.007-.309 1.496-.501c.706-.275 1.496-.66 1.873-1.355c.193-.356.26-.766.26-1.167A7.001 7.001 0 0 0 5.55 8.276A6.9 6.9 0 0 0 5 11a1 1 0 0 1-2 0a8.9 8.9 0 0 1 .708-3.504");
}

</style>
