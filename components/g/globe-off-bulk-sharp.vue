<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tdibvxbty"/><path class="xiwo6v7ss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:globe-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.tdibvxbty {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.876 4.633L7.374 3.131a10.004 10.004 0 0 1 13.495 13.495Zm-3.947.296l14.142 14.142c-3.905 3.905-10.237 3.905-14.142 0s-3.905-10.237 0-14.142");
}

.xiwo6v7ss {
  d: path("m21.293 22.707l-4.792-4.792c-.529 1.426-1.43 2.868-2.791 3.621A3.54 3.54 0 0 1 12 22h-.003c-.867-.001-1.626-.395-2.244-.983c-.657-.626-1.13-1.424-1.496-2.247c-.788-1.776-1.144-3.835-1.234-5.77H3a1 1 0 0 1 0-2h3.968c-.042-.88-.112-1.766-.027-2.645L1.293 2.707a.999.999 0 1 1 1.414-1.414l20 20a.999.999 0 1 1-1.414 1.414M8.938 10.352L8.97 11h.616ZM11.586 13H9.025q.058 1.168.272 2.318c.17.903.414 1.798.788 2.64c.259.582.581 1.166 1.047 1.61c.234.223.532.432.868.432c.262 0 .515-.088.741-.214c.338-.186.624-.454.871-.748c.649-.775 1.046-1.747 1.292-2.72Z");
}

</style>
