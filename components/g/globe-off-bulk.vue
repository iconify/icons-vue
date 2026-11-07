<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tdibvxbty"/><path class="doajd-bxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:globe-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.doajd-bxm {
  d: path("m21.293 22.707l-5.106-5.106c-.452 1.397-1.21 2.978-2.448 3.831c-.514.353-1.112.568-1.739.568c-.868 0-1.628-.394-2.247-.983c-.657-.626-1.13-1.424-1.496-2.247c-.788-1.776-1.144-3.835-1.234-5.77H3a1 1 0 0 1 0-2h4.023a20 20 0 0 1 .243-2.32L1.293 2.707a.999.999 0 1 1 1.414-1.414l20 20a.999.999 0 1 1-1.414 1.414M9.06 10.474q-.021.262-.035.526h.561ZM11.586 13H9.025q.058 1.168.272 2.318c.17.903.414 1.798.788 2.64c.259.582.581 1.166 1.047 1.61c.234.223.532.432.868.432c.577 0 1.087-.617 1.376-1.048c.587-.875.948-1.954 1.188-2.974Z");
}

.tdibvxbty {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.876 4.633L7.374 3.131a10.004 10.004 0 0 1 13.495 13.495Zm-3.947.296l14.142 14.142c-3.905 3.905-10.237 3.905-14.142 0s-3.905-10.237 0-14.142");
}

</style>
