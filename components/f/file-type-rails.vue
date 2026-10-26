<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="pgrq0gb6f"><path class="p1j31z63s"/><path class="z_y57wbup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-rails" /></template>
<style>
.p1j31z63s {
  d: path("m17.32 7.4l.24.77h-.11l-.82.02l-.26.03l-.24-.73q.62-.08 1.19-.08m4.72.73c.73.21 1.04.36 1.17.43h.02l-.05.84q-.39-.17-.79-.31l-.4-.14zm-10.16.47l.55.85q-.36.18-.7.4l-.25.15l-.57-.86q.5-.3.97-.54M22.02 12q.46.04.97.12l.24.05l-.05.77a7 7 0 0 0-.98-.14h-.24zm-2.9.31l.28.82q-.43.13-.87.32l-.21.1l-.29-.85q.47-.2 1.09-.39m-12.23.05l.88.77q-.34.34-.65.72l-.2.25l-.95-.82q.43-.46.92-.92m8.84 1.82l.55.85q-.32.33-.6.69l-.12.18l-.6-.9q.34-.42.77-.81m-2.19 3.45l.9.69q-.17.59-.23 1.16l-.04.28l-1-.78q.14-.68.37-1.36m-10.92.49l1.42.52l-.56 1.31l-.06.17L2 19.6c.12-.33.38-.94.62-1.48m10.37 4l1.33.48q.1.74.25 1.36l.05.25l-1.49-.53q-.1-.57-.14-1.56");
}

.pgrq0gb6f {
  fill: var(--svg-color--c81418, #c81418);
}

.z_y57wbup {
  d: path("m29.98 14.39l.02.02s-.21.14-.43.32c-7.02-5.18-11.3-2.74-12.64-2.08c-6.12 3.41-4.35 11.78-4.31 11.94H2.86s.38-3.64 2.97-7.97s7-7.58 10.6-7.9c6.93-.7 13.17 5.3 13.55 5.66");
}

</style>
