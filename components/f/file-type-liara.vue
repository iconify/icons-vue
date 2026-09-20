<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGNPpMqcvO" x1="11.328" x2="90.301" y1="8.203" y2="10.761" gradientTransform="matrix(.15939 0 0 .16254 6.386 6.039)" gradientUnits="userSpaceOnUse"><stop offset="0" class="e6ohnx83n"/><stop offset="1" class="fqlolabaa"/></linearGradient><linearGradient id="SVGLDbOjcXX" x1="11.328" x2="90.301" y1="8.203" y2="10.761" gradientTransform="matrix(.15939 0 0 .16253 6.715 6.04)" gradientUnits="userSpaceOnUse"><stop offset="0" class="e6ohnx83n"/><stop offset="1" class="fqlolabaa"/></linearGradient><linearGradient id="SVGJIL2cevG" x1="11.328" x2="90.301" y1="8.203" y2="10.761" gradientTransform="matrix(.15784 0 0 .16493 6.67 6.54)" gradientUnits="userSpaceOnUse"><stop offset="0" class="e6ohnx83n"/><stop offset="1" class="fqlolabaa"/></linearGradient></defs><path fill="url(#SVGNPpMqcvO)" transform="translate(-15.199 -15.044)scale(2.1596)" class="u569mhiwv"/><path fill="url(#SVGLDbOjcXX)" transform="translate(-15.199 -15.044)scale(2.1596)" class="fmbswyqjk"/><path fill="url(#SVGJIL2cevG)" transform="translate(-15.199 -15.044)scale(2.1596)" class="zi_uwnb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-liara" /></template>
<style>
.e6ohnx83n {
  stop-color: var(--svg-color--69f0ae, #69f0ae);
}

.fmbswyqjk {
  d: path("M8.52 12.489c0-.53.368-.745.82-.479l3.86 2.258c.452.264.82.909.82 1.44v4.595c0 .53-.368.744-.82.48l-3.86-2.262c-.452-.264-.82-.909-.82-1.44z");
}

.fqlolabaa {
  stop-color: var(--svg-color--4fc3f7, #4fc3f7);
}

.u569mhiwv {
  d: path("M15.02 15.707c0-.53.368-1.174.82-1.44l3.86-2.257c.452-.265.82-.052.82.479v4.596c0 .527-.368 1.17-.82 1.436l-3.86 2.261c-.452.265-.82.051-.82-.479z");
}

.zi_uwnb7f {
  d: path("M9.856 11.363c-.448-.27-.448-.706 0-.972l3.821-2.293c.447-.27 1.173-.27 1.62 0l3.888 2.332c.447.268.447.702 0 .971l-3.822 2.294c-.447.268-1.173.268-1.624 0z");
}

</style>
