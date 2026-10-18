<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cg01babel"><path class="fp76ad3zj"/><path class="vgrcl7u2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-slint" /></template>
<style>
.cg01babel {
  fill: var(--svg-color--2379f4, #2379f4);
  stroke-width: var(--svg-stroke-width--0-963px, 0.963px);
}

.fp76ad3zj {
  d: path("m9.394 29.918l16.355-10.98s.738-.408.738-1.057c0-.864-.933-1.143-.933-1.143l-8.997-3.45c-.322-.123-.765.218-.35.652l2.978 2.888s.828.789.828 1.305c0 .517-.507.976-.507.976L8.666 29.254c-.385.361.136 1.015.728.664");
}

.vgrcl7u2e {
  d: path("M22.605 2.082L6.25 13.062s-.737.41-.737 1.059c0 .862.932 1.144.932 1.144l8.998 3.448c.322.12.765-.22.35-.651l-2.978-2.897s-.83-.788-.83-1.305c0-.519.51-.976.51-.976L23.327 2.745c.392-.36-.128-1.016-.721-.663z");
}

</style>
