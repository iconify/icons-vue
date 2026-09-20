<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":328};
const content = `<path class="kwph9cukf"/><path class="hmebrpbjb"/><path class="xph-7ibfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:beats" /></template>
<style>
.hmebrpbjb {
  fill: var(--svg-color--343741, #343741);
  d: path("M208.262 138.798c-15.826-10.024-34.534-15.917-54.663-15.917H.001v81.921h112.638c43.715 0 80.932-27.446 95.623-66.004");
}

.kwph9cukf {
  fill: var(--svg-color--07c, #07c);
  d: path("M208.262 138.798c-14.691 38.558-51.908 66.004-95.623 66.004H0V0h112.638C169.2 0 215.04 45.851 215.04 102.401c0 12.84-2.464 25.074-6.778 36.397");
}

.xph-7ibfg {
  fill: var(--svg-color--00bfb3, #00bfb3);
  d: path("M232.316 159.811c-21.451 44.529-67.036 75.337-119.678 75.337H0v92.54h153.599c56.562 0 102.401-45.85 102.401-102.4c0-24.91-8.902-47.727-23.684-65.477");
}

</style>
