<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bjexm-byy"/><path class="ax7i_rv0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-sync-corner-bulk-sharp" /></template>
<style>
.ax7i_rv0a {
  d: path("M12 3a1.002 1.002 0 0 1 1.707-.707l6 6A1 1 0 0 1 19 10h-6a1 1 0 0 1-1-1Zm2 5h2.586L14 5.414Zm4 6h.748a5 5 0 0 0-.195-.106l-.002-.001a3.474 3.474 0 0 0-4.657 1.554a1 1 0 1 1-1.788-.894a5.4 5.4 0 0 1 1.025-1.422A5.464 5.464 0 0 1 20 12.423V12a1 1 0 0 1 2 0v3a1 1 0 0 1-.548.892h-.002l-.001.002h-.001v.001h-.003l-.001.001c-.138.068-.29.104-.444.104h-3a1 1 0 0 1 0-2m-4 7.577V22a1 1 0 0 1-2 0v-3a1 1 0 0 1 .552-.894l.002-.001l.002-.001a1 1 0 0 1 .407-.103h.001L13 18h3a1 1 0 0 1 0 2h-.748a3.47 3.47 0 0 0 4.854-1.447a1 1 0 1 1 1.788.894a5.4 5.4 0 0 1-1.025 1.422a5.4 5.4 0 0 1-1.421 1.025A5.46 5.46 0 0 1 14 21.577");
}

.bjexm-byy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 2c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10h-9v11a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm0 6h4l-4-4Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

</style>
