<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u4m3yibhc"/><path class="mu44widdc"/><path class="sk1z99b8b"/><path class="rhs9_6pho"/><path class="n2bmiybgo"/><path class="vy2zk-f3a"/><path class="axwtahbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:level-slider" /></template>
<style>
.axwtahbiy {
  fill: var(--svg-color--fff, #fff);
  d: path("M43.5 111.08c0 .97-.78 1.75-1.75 1.75s-1.75-.78-1.75-1.75V13.7c0-.97.78-1.75 1.75-1.75s1.75.78 1.75 1.75z");
}

.mu44widdc {
  fill: var(--svg-color--cfd8dc, #cfd8dc);
  d: path("M91.92 115.52c0 5.22-4.5 9.45-10.05 9.45H49.05c-5.55 0-10.05-4.23-10.05-9.45V9.45C39 4.23 43.5 0 49.05 0h32.83c5.55 0 10.05 4.23 10.05 9.45v106.07z");
}

.n2bmiybgo {
  fill: var(--svg-color--37474f, #37474f);
  d: path("M79.77 90.65c0 1.3-.87 2.35-1.94 2.35h-24.7c-1.07 0-1.94-1.05-1.94-2.35V83.4c0-1.3.87-2.35 1.94-2.35h24.7c1.07 0 1.94 1.05 1.94 2.35z");
}

.rhs9_6pho {
  fill: var(--svg-color--546e7a, #546e7a);
  d: path("M64.42 15.04h2.12v93.87h-2.12zm-15.89-1.69h7.75v2.61h-7.75zm0 11.88h7.75v2.61h-7.75zm0 11.88h7.75v2.61h-7.75zm0 11.88h7.75v2.61h-7.75zm0 11.88h7.75v2.61h-7.75zm0 11.88h7.75v2.61h-7.75zm0 11.88h7.75v2.61h-7.75zm0 11.87h7.75v2.61h-7.75zm0 11.88h7.75v2.61h-7.75zm25.99-95.03h7.75v2.61h-7.75zm0 11.88h7.75v2.61h-7.75zm0 11.88h7.75v2.61h-7.75zm0 11.88h7.75v2.61h-7.75zm0 11.88h7.75v2.61h-7.75zm0 11.88h7.75v2.61h-7.75zm0 11.88h7.75v2.61h-7.75zm0 11.87h7.75v2.61h-7.75zm0 11.88h7.75v2.61h-7.75z");
}

.sk1z99b8b {
  fill: var(--svg-color--90a4ae, #90a4ae);
  d: path("M61.46 11.95h8.04V112h-8.04z");
}

.u4m3yibhc {
  fill: var(--svg-color--90a4ae, #90a4ae);
  d: path("M96.09 115.16c0 5.35-3.52 12.84-9.41 12.84H44.41c-5.89 0-9.41-7.5-9.41-12.84V10.68C35 5.34 39.78 0 45.67 0h39.75c5.89 0 10.67 5.34 10.67 10.68z");
}

.vy2zk-f3a {
  fill: var(--svg-color--546e7a, #546e7a);
  d: path("M79.77 83.15c0 1.07-.87 0-1.94 0h-24.7c-1.07 0-1.94 1.07-1.94 0v-.17c0-1.07.87-1.94 1.94-1.94h24.7c1.07 0 1.94.87 1.94 1.94z");
}

</style>
