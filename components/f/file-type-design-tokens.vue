<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="u77uolbhp"><path class="oi3x-zlqw"/><path class="q9s526qxe"/><path class="d86n6of_u"/><path class="r4ewhnb4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-design-tokens" /></template>
<style>
.d86n6of_u {
  d: path("M16 29.6L4.18 22.91l5.8-3.34l2.67 2.23L16 22.9l3.34-1.11l2.68-2.23l5.8 3.34z");
  opacity: var(--svg-opacity--0-75, 0.75);
}

.oi3x-zlqw {
  d: path("M4.18 9.31L16 2.62V9.1l-4.46 1.78l-2.23 4.46l.9 4.02l-6.03 3.34z");
  opacity: var(--svg-opacity--0-25, 0.25);
}

.q9s526qxe {
  d: path("M28.04 9.09L16 2.39v6.7l4.9 2l1.79 4.24l-.9 4.02l6.25 3.34z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.r4ewhnb4x {
  d: path("M15.55 2.06a1.8 1.8 0 0 1 1.33.18l10.7 6.11q.21.12.38.3l.03.02c.3.33.49.77.49 1.23v12.2c0 .64-.34 1.23-.9 1.55l-10.7 6.12q-.21.12-.44.17l-.15.04h-.04l-.17.02h-.05a2 2 0 0 1-.44-.05h-.04l-.33-.13l-.1-.05l-10.7-6.12c-.56-.32-.9-.9-.9-1.55V9.9q0-.25.06-.48V9.4l.03-.08V9.3l.03-.06l.08-.16l.02-.03l.09-.15l.02-.04a2 2 0 0 1 .46-.44l.1-.06l10.7-6.11q.21-.12.44-.18M4.86 22.88l10.69 6.1v-5.86a7.1 7.1 0 0 1-5.52-3.2zm17.1-2.96a7.1 7.1 0 0 1-5.51 3.2v5.87l10.69-6.11zm-11.59-6.63a6.2 6.2 0 0 0 .3 5.96a6.2 6.2 0 0 0 4.88 2.97v-5.96zm6.08 2.97v5.96a6.24 6.24 0 0 0 5.18-8.93zM4.4 22.1l5.19-2.97a7.1 7.1 0 0 1 0-6.3L4.4 9.89zm18-9.26a7.1 7.1 0 0 1 0 6.3l5.19 2.96V9.88zM16 9.75a6.3 6.3 0 0 0-5.2 2.77l5.2 2.96l5.18-2.96A6.2 6.2 0 0 0 16 9.75M4.85 9.12l5.18 2.95a7.1 7.1 0 0 1 5.52-3.2V3.02zm11.6-.25a7.1 7.1 0 0 1 5.5 3.2l5.19-2.95L16.45 3z");
}

.u77uolbhp {
  fill: var(--svg-color--2b5cf2, #2b5cf2);
}

</style>
