<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nygha_b7t"/><path class="nbf7r3bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-wasp" /></template>
<style>
.nbf7r3bnx {
  fill: var(--svg-color--111, #111);
  d: path("M6.6 11.76h9.22v2.95H6.6zm0 5.53h9.22v2.95H6.6zm13.95-9.76h-2.9l.02 2.62h1.58s.34.03.56.15c.25.13.27.2.4.37q.1.13.11.3l.03.18v2.66l.03.3c.03.16.06.35.1.48c.08.21.25.49.4.67q.27.3.65.5c.2.12.6.22.61.22v.04a2.4 2.4 0 0 0-1.26.72a3 3 0 0 0-.4.67c-.04.13-.08.32-.1.49l-.03.29v2.66l-.03.18a1 1 0 0 1-.11.3c-.13.17-.15.24-.4.37c-.22.12-.56.15-.56.15h-1.58l-.01 2.62h3.19l.46-.05a3 3 0 0 0 1.03-.37c.22-.12.45-.35.64-.6c.19-.23.34-.5.4-.68c.1-.38.11-.87.11-.87v-3.6l.04-.27l.1-.22q.08-.14.15-.2c.1-.08.24-.18.38-.2l.24-.03h1v-2.76h-1l-.24-.03c-.14-.02-.27-.12-.38-.2l-.15-.2l-.1-.22l-.03-.16l-.01-.11v-3.6s0-.49-.12-.87c-.05-.19-.2-.45-.4-.69a3 3 0 0 0-.63-.6l-.41-.2c-.25-.1-.49-.14-.62-.16a4 4 0 0 0-.76-.05");
}

.nygha_b7t {
  fill: var(--svg-color--f5c842, #f5c842);
  d: path("M2 2v28h28V2");
}

</style>
