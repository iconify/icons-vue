<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVG8kkBecXM" x1="11.08" x2="11.08" y1="31.2" y2="15.71" gradientTransform="matrix(1 0 0 .99 0 -14.32)" gradientUnits="userSpaceOnUse"><stop offset="0" class="a5n6nll5q"/><stop offset=".33" class="dgp0bdcxg"/><stop offset=".82" class="a6ue6uoip"/><stop offset="1" class="vyv65fbev"/></linearGradient></defs><path fill="url(#SVG8kkBecXM)" transform="translate(2 2.02)scale(1.55592)" class="v-p3vobmp"/><path class="f3ce6objo"/><path class="ye9ik5b4c"/><path class="yxi21009j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-azurestreamanalytics" /></template>
<style>
.a5n6nll5q {
  stop-color: var(--svg-color--949494, #949494);
}

.a6ue6uoip {
  stop-color: var(--svg-color--aeafb0, #aeafb0);
}

.dgp0bdcxg {
  stop-color: var(--svg-color--9b9b9b, #9b9b9b);
}

.f3ce6objo {
  fill: var(--svg-color--50e6ff, #50e6ff);
  d: path("M8.22 18.59a5.6 5.6 0 0 1-3.99-1.63a.72.72 0 1 1 1.01-.94a4.1 4.1 0 0 0 2.98 1.14a4 4 0 0 0 2.92-1.14a5.5 5.5 0 0 1 3.97-1.55a5.7 5.7 0 0 1 4 1.55a.72.72 0 1 1-1.01 1.02a4.2 4.2 0 0 0-2.94-1.22a4 4 0 0 0-2.93 1.21a5.6 5.6 0 0 1-4.01 1.56");
}

.v-p3vobmp {
  d: path("M18 9.69V7.9l-.1-.09l-1.84-.62L15.59 6l.91-1.88l.1-.21l-.6-.61l-.7-.69l-.24.12l-1.8.91l-1.21-.34l-.78-2H9.48l-.09.09l-.62 1.83l-1.26.47l-2.08-1l-1.28 1.25l.12.24L5.23 6a6 6 0 0 1 3.2-.86A6.3 6.3 0 0 1 12 6.28l.36.26a3 3 0 0 1 .93 1.35A3 3 0 0 1 13.5 9a3.23 3.23 0 0 1-3.25 3.23a3.3 3.3 0 0 1-1.87-.59a6.3 6.3 0 0 1-4 1.75l-.19.39l1.28 1.29l.26-.07l1.8-1l1.24.51l.79 2.16h1.8l.07-.25l.64-1.91l1.22-.51l2.11 1l1.27-1.26l-.12-.24l-.93-1.79l.38-1.25Z");
}

.vyv65fbev {
  stop-color: var(--svg-color--b6b8b9, #b6b8b9);
}

.ye9ik5b4c {
  fill: var(--svg-color--50e6ff, #50e6ff);
  d: path("M8.22 15.74a2.8 2.8 0 0 1-1.96-.8a.72.72 0 0 1 1-1.02a1.3 1.3 0 0 0 .96.4a1.7 1.7 0 0 0 .93-.4a8.5 8.5 0 0 1 11.93 0a.72.72 0 0 1-1 1.01a7.1 7.1 0 0 0-9.98 0a3 3 0 0 1-1.88.81");
}

.yxi21009j {
  fill: var(--svg-color--32bedd, #32bedd);
  d: path("M8.22 21.44a8.4 8.4 0 0 1-6.02-2.48a.73.73 0 0 1 0-1a.73.73 0 0 1 1.02 0a7 7 0 0 0 5 2.06a7 7 0 0 0 4.98-2.07a3 3 0 0 1 1.88-.76a2.9 2.9 0 0 1 1.94.81a.7.7 0 0 1 0 1.01a.73.73 0 0 1-1.02 0a1.3 1.3 0 0 0-.92-.39a1.6 1.6 0 0 0-.93.4a8.4 8.4 0 0 1-5.93 2.42");
}

</style>
