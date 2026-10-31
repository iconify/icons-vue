<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o0ptc_z3q"/><path class="h7whymbix"/><path class="vv5y1y95d"/><path class="mlri1xbzd"/><defs><ellipse id="SVGS3D2INlN" class="acfeyhcsc"/></defs><g class="p-y-ynvdy"><use x="10.22" y="18.36" href="#SVGS3D2INlN"/><use x="6.75" y="19.82" href="#SVGS3D2INlN"/><use x="7.93" y="19.8" href="#SVGS3D2INlN"/><use x="5.55" y="21.06" href="#SVGS3D2INlN"/><use x="6.77" y="21.04" href="#SVGS3D2INlN"/><use x="7.94" y="21.02" href="#SVGS3D2INlN"/><use x="6.78" y="22.27" href="#SVGS3D2INlN"/><use x="5.58" y="23.45" href="#SVGS3D2INlN"/></g><path class="px4kmi4hu"/><circle class="zic25znyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-ghidra" /></template>
<style>
.acfeyhcsc {
  rx: 0.33px;
  ry: 0.41px;
}

.h7whymbix {
  fill: var(--svg-color--ff9e18, #ff9e18);
  d: path("M23.35 14.66c2.87 2.93 3.32 10.3-5.48 13.58c-4.92.96-10.16-2.16-12.52-3.8C8.53 25.98 13 27.9 17 27.12c6.16-1.24 8.78-5.37 7.75-10.1a4 4 0 0 0-1.4-2.36");
}

.mlri1xbzd {
  fill: var(--svg-color--ff7f40, #ff7f40);
  d: path("M18.3 11.3c.97 2.44.76 4.34-1.95 4.5c1.75-1 2.36-2.5 1.96-4.5m-2.6 4.9a26 26 0 0 1-2.33 6.5c-.35.65-1.55.1-2.3-.57c.73.13 1.2.2 1.5.13c.8-.17 2.1-3.3 3.15-6.04");
}

.o0ptc_z3q {
  fill: var(--svg-color--e1251b, #e1251b);
  stroke: var(--svg-color--672f25, #672f25);
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M24.7 5.55c-2.1-.3-4.6 1.07-6.4 2.92c.6-1.54 1.91-2.83 4.35-3.39c-3.61-1.13-7.13 1.11-9.32 4.02l-1.4-.28c-1.37-.28-1.7.79-2.14 2.19c-.7 2.25-2.55 2.39-4.53 3.04c-2.1.69-2.88 3.16-1.04 5.01c.1-1.03.43-1.8 1.12-2.2c-.31 1.07.35 1.53 1.97 1.81c-.77-.77-.92-1.39-.46-2.01c.23.73.87 1.03 1.65.94c-.46-.34-.83-.75-.67-1.32c.68.21 1.26.48 1.8.2c.54-.29.63-1.4 1.25-1.92c.42-.36 1.41-.7 2.17-.39c-1.52-.39-1.54.49-1.18 1.64c.23.76.89 1.59.81 2.4l-.2 2.55c-.07 1.03-.29 1.39-3.02.99c.92 1.27 2.1 2.26 3.4 2.38c.62.05.77-.41 1.03-.98l2.61-6.7c1.92.24 2.95-1.42 3.1-2.8a4.35 4.35 0 0 1 5.15 3.38c1.03 4.72-1.59 8.85-7.75 10.09c-4 .78-8.47-1.14-11.65-2.67A13.6 13.6 0 1 0 24.7 5.55Z");
}

.p-y-ynvdy {
  fill: none;
  stroke: var(--svg-color--f7be00, #f7be00);
  stroke-width: var(--svg-stroke-width--0-16px, 0.16px);
}

.px4kmi4hu {
  fill: var(--svg-color--f7be00, #f7be00);
  d: path("m8.9 19.1l-.17.05l-.04-.14l.26-.1h.12v1h-.15Zm-4.6 1.67l-.18.05l-.04-.13l.26-.1h.1l.02.96H4.3Zm0 1.23l-.17.05l-.03-.13l.25-.1h.12v.96h-.16Zm1.28 0l-.17.04l-.04-.14l.26-.08h.1l.02.94h-.16Zm-1.26 1.17l-.17.05l-.04-.14l.26-.08h.1l.02.95h-.16Z");
}

.vv5y1y95d {
  fill: var(--svg-color--672f25, #672f25);
  d: path("m10.54 12.06l1.3-.47l-.1-2.1a6.4 6.4 0 0 1-1.2 2.57M5 15.1l1.23-.53l-.03.4Zm13.3-5c1.44.7 2.4 1.8 2.74 3.44l-1.44.14a5.3 5.3 0 0 0-1.3-3.6");
}

.zic25znyv {
  cx: 16px;
  cy: 16px;
  r: 13.6px;
  fill: none;
  stroke: var(--svg-color--231f20, #231f20);
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
}

</style>
