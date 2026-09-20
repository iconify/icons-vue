<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z38ne3usi"/><path class="nais9o4xl"/><ellipse class="jlmtc9bgb"/><ellipse class="urte1bcpd"/><ellipse class="gy8doqksu"/><ellipse class="vx9c_db-g"/><path class="b7io1_b4j"/><path class="d9pp6ob9g"/><linearGradient id="SVG0NlYz2eG" x1="16" x2="16" y1="3.54" y2="28.41" gradientUnits="userSpaceOnUse"><stop offset="0" class="g_axnurnj"/><stop offset=".02" class="iefwmkbkj"/><stop offset=".07" class="anhu-0bha"/><stop offset=".13" class="zj222pbid"/><stop offset=".19" class="qg1gvlm4y"/><stop offset=".26" class="yb921edfn"/><stop offset=".33" class="x2rzhbc8q"/><stop offset=".42" class="co5bb3b_l"/><stop offset=".52" class="ly5bp1-7y"/><stop offset=".66" class="gkgafhbra"/><stop offset="1" class="lnl-ymbiz"/></linearGradient><path fill="url(#SVG0NlYz2eG)" class="ftuppgnvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-lintstagedrc" /></template>
<style>
.anhu-0bha {
  stop-color: var(--svg-color--f5b2a4, #f5b2a4);
}

.b7io1_b4j {
  fill: var(--svg-color--ebebeb, #ebebeb);
  d: path("M20.6 21.4c-.37-.53-1.5-.04-4.64-.04c-3.13 0-4.27-.5-4.63.04c-.46.66 1.65 2.64 4.63 2.7c2.98-.06 5.1-2.05 4.64-2.7");
}

.co5bb3b_l {
  stop-color: var(--svg-color--e43916, #e43916);
}

.d9pp6ob9g {
  fill: var(--svg-color--bc2100, #bc2100);
  d: path("M28.98 10.73A13.9 13.9 0 0 0 25.9 6.1A13.95 13.95 0 0 0 16 2a13.95 13.95 0 0 0-9.9 4.1A13.95 13.95 0 0 0 2 16a13.95 13.95 0 0 0 4.1 9.9a13.9 13.9 0 0 0 4.63 3.07C12.41 29.66 14.18 30 16 30a13.95 13.95 0 0 0 9.9-4.1a13.9 13.9 0 0 0 3.07-4.63a13.94 13.94 0 0 0 0-10.54zM16 26.68c-2.85 0-5.53-1.11-7.55-3.13S5.32 18.85 5.32 16c0-2.3.72-4.47 2.04-6.29L22.3 24.63a10.6 10.6 0 0 1-6.3 2.05m8.63-4.4L9.71 7.37A10.6 10.6 0 0 1 16 5.33c2.85 0 5.53 1.11 7.55 3.13s3.13 4.7 3.13 7.55c0 2.3-.72 4.47-2.04 6.29z");
}

.ftuppgnvv {
  d: path("M16 29.36a13.3 13.3 0 0 1-9.45-3.91A13.3 13.3 0 0 1 2.65 16a13.3 13.3 0 0 1 3.9-9.45A13.3 13.3 0 0 1 16 2.65a13.3 13.3 0 0 1 9.45 3.9a13.32 13.32 0 0 1 3.9 9.45a13.3 13.3 0 0 1-3.9 9.45a13.3 13.3 0 0 1-9.45 3.9zM6.85 9.34A11.2 11.2 0 0 0 4.68 16c0 3.02 1.18 5.87 3.32 8a11.28 11.28 0 0 0 14.66 1.15l.6-.44L7.3 8.73l-.44.6zM16 4.68c-2.42 0-4.73.75-6.67 2.17l-.6.44l15.98 15.98l.44-.6A11.22 11.22 0 0 0 27.32 16c0-3.02-1.18-5.87-3.32-8s-4.98-3.32-8-3.32");
}

.g_axnurnj {
  stop-color: var(--svg-color--fce7e2, #fce7e2);
}

.gkgafhbra {
  stop-color: var(--svg-color--e12902, #e12902);
}

.gy8doqksu {
  cx: 20.22px;
  cy: 16.55px;
  fill: var(--svg-color--e9e8e5, #e9e8e5);
  rx: 2.71px;
  ry: 3.34px;
}

.iefwmkbkj {
  stop-color: var(--svg-color--fad6ce, #fad6ce);
}

.jlmtc9bgb {
  cx: 12.05px;
  cy: 16.55px;
  fill: var(--svg-color--e9e8e5, #e9e8e5);
  rx: 2.71px;
  ry: 3.34px;
}

.lnl-ymbiz {
  stop-color: var(--svg-color--e12700, #e12700);
}

.ly5bp1-7y {
  stop-color: var(--svg-color--e22f09, #e22f09);
}

.nais9o4xl {
  fill: var(--svg-color--543119, #543119);
  d: path("M28.38 23.74c0-1.59-.82-2.5-1.66-3.01c1.89 3.45-4.42 5.31-12.1 5.87c1.46.08 2.35.3 6.62.3c1.9 0 7.14.08 7.14-3.16m-22 3.17c.81 0 2.02-.09 3.32-.18c-2.3-.37-4.99-1.37-5.93-3.97c-.47 1.93.51 4.15 2.6 4.15zm17.84-11.52c1.1 3.24-.84 6.12-2.9 7.52c.87-.54 2.32-1.58 3.62-2.83c1.22-2.42.31-3.88-.73-4.69zm-1.66-.95c.62-1.8-.11-2.78-1-3.3c.68 4.47-2.8 5.71-9.39 8.6c0 0 6.81-1.39 10.39-5.3m-12.67 5.3c-.72-.24-2.22.14-3.43-2.48a4.1 4.1 0 0 0 .3 2.57c1.48.15 3.13-.1 3.13-.1zm8.15-13.76c1.75 5.13-2.44 6.68-8.76 8.7c0 0 7.62-1.56 10.3-4.14c.49-1.8-.33-3.35-1.54-4.56M15.6 7.16s-2.7 2.9-2.26-1.89c-.39.78-1.14 1.84-1.14 2.54c0 .49.18.82.28 1.03c2.65-.25 3.12-1.68 3.12-1.68");
}

.qg1gvlm4y {
  stop-color: var(--svg-color--ec745b, #ec745b);
}

.urte1bcpd {
  cx: 11.98px;
  cy: 16.65px;
  fill: var(--svg-color--0a0a0a, #0a0a0a);
  rx: 1.36px;
  ry: 2.15px;
}

.vx9c_db-g {
  cx: 20.15px;
  cy: 16.65px;
  fill: var(--svg-color--0a0a0a, #0a0a0a);
  rx: 1.36px;
  ry: 2.15px;
}

.x2rzhbc8q {
  stop-color: var(--svg-color--e64827, #e64827);
}

.yb921edfn {
  stop-color: var(--svg-color--e85c3e, #e85c3e);
}

.z38ne3usi {
  fill: var(--svg-color--875430, #875430);
  d: path("M6.83 20c-1.45-3.08.84-5.32 2.45-5.32c-.93-3.35 1.02-5.55 3.02-5.55c.57 0-.11-.37-.11-1.32s1.36-2.53 1.36-3.2s-.74-1.04-.42-1.36s7.7 2.67 6.46 7.28c0 0 4.28.28 2.94 4c0 0 4.59 1.23 2.41 5.55c0 0 3.44.41 3.44 3.66s-5.25 3.17-7.13 3.17c-5.25 0-5.4-.34-7.74-.34s-5.51.34-7.13.34c-3.51 0-3.91-6.24.45-6.91");
}

.zj222pbid {
  stop-color: var(--svg-color--f0917c, #f0917c);
}

</style>
