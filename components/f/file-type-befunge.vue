<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect class="rpl0lp2_f"/><path class="u-ql08xpg"/><path class="xr8rksa0k"/><path class="pt4uy_brr"/><path class="qd4w4ebrd"/><path class="iskh4bc9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-befunge" /></template>
<style>
.iskh4bc9v {
  fill: var(--svg-color--e8e8e8, #e8e8e8);
  d: path("M15.84 19.05h2.7a4.3 4.3 0 0 1 2.4.53a1.8 1.8 0 0 1 .76 1.63a2.2 2.2 0 0 1-.33 1.25a1.5 1.5 0 0 1-.89.66v.06a1.8 1.8 0 0 1 1.05.71a2.6 2.6 0 0 1-.47 3.15a3.3 3.3 0 0 1-2.18.68h-3.04Zm2.11 3.33h.6a1 1 0 0 0 .74-.2a.8.8 0 0 0 .25-.62q0-.73-1-.73h-.6Zm0 1.7v1.84h.75q.99 0 .99-.93a.8.8 0 0 0-.27-.66a1 1 0 0 0-.76-.24Zm7.32 3.64h-2.08v-8.67h4.62v1.88h-2.54v1.66h2.34v1.88h-2.34Z");
}

.pt4uy_brr {
  fill: var(--svg-color--1976d2, #1976d2);
  d: path("M17.47 5.88c1.5 0 2.45.74 2.45 1.94c0 1.16-1.26 1.85-1.43 1.97c-.84.6-.8.6-.8 1.75h-1.37c0-1.12-.11-1.74.66-2.36c.61-.48 1.32-.65 1.32-1.24c0-.25-.3-.46-.84-.46a3.3 3.3 0 0 0-1.54.5l-.85-1.15a3.4 3.4 0 0 1 2.4-.95m-1.19 6.18h1.46v1.48h-1.46Zm10.37 1.48v.76h-4.1v-.75Z");
}

.qd4w4ebrd {
  fill: var(--svg-color--512da8, #512da8);
  d: path("M10.33 19.84h1.46v1.49h-1.46Zm0 3.02h1.46v1.5h-1.46Zm12.13 1.74v.85H21.4v-.8a3.5 3.5 0 0 1-2.1-1.05l.84-.96a3 3 0 0 0 1.67.57c.58 0 .92-.22.92-.6c0-.43-.9-.74-1.5-1c-1.17-.52-1.84-1.02-1.78-2.07a2.05 2.05 0 0 1 1.94-1.82v-.84l1.04-.1v.95a4.5 4.5 0 0 1 1.76.73l-.7 1.03a3 3 0 0 0-1.4-.4c-.6-.01-.98.2-.98.53c0 .42.5.54 1.09.78c1.35.57 2.21 1.1 2.21 2.19a2.14 2.14 0 0 1-1.95 2");
}

.rpl0lp2_f {
  width: 26.99px;
  height: 26.99px;
  x: 2.51px;
  y: 2.51px;
  fill: var(--svg-color--1e1e1e, #1e1e1e);
  stroke: var(--svg-color--5b5b5b, #5b5b5b);
  stroke-width: var(--svg-stroke-width--1-01px, 1.01px);
  rx: 1.69px;
}

.u-ql08xpg {
  fill: var(--svg-color--ffc107, #ffc107);
  d: path("m9.97 8.69l-2.12 4.9H6.8l-2.12-4.9h1.58l1.07 2.84L8.4 8.69ZM9.4 21.12v.4l-4 2.46v-.87l2.94-1.79l-2.94-1.78v-.86Zm4.03-4.14h.75v8.2h-.75Zm3.14.5h.79l1.2 2.26h-.5l-1.1-1.68l-1.1 1.68h-.5Z");
}

.xr8rksa0k {
  fill: var(--svg-color--009688, #009688);
  d: path("M15.16 10.9h-2.15v2.16h-.76v-2.15H10.1v-.75h2.15V8h.76v2.16h2.15Zm6.37 2.3l-.84 1.86l-1.1.21l.7-2.09Z");
}

</style>
