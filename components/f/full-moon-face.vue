<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xthtgwbai"/><g class="ehej3-bmx"><path class="o46k1jkal"/><ellipse class="t556zx4mp"/><ellipse class="fmm08q0xe"/><path class="ftgp97b9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:full-moon-face" /></template>
<style>
.ehej3-bmx {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.fmm08q0xe {
  cx: 90.26px;
  cy: 58.24px;
  rx: 7.22px;
  ry: 7.96px;
}

.ftgp97b9c {
  d: path("M71.39 75.08c-2.35-1.15-2.57 3.06-7.38 3.06c-2.81 0-6.26-1.96-6.2-5.08c.02-.57.03-1.09.17-1.65c.16-.63.38-1.19.6-1.8c.44-1.17 1-2.29 1.5-3.43c.4-.89.75-1.81 1.04-2.74c1.35-4.37 1.4-9.12-1.1-13.17c-.33-.53-.62-1.13-1.11-1.5c-1.6-1.24-2.57.26-2.31 1.72c.38 2.18 1.67 4.02 1.89 6.28c.33 3.35-.61 7.12-2.25 10.08c-.23.41-.5.83-.7 1.27c-1.06 2.32-1.86 5.03-.87 7.57c1.39 3.54 5.69 5.75 9.35 5.75c6.26.01 9.72-5.2 7.37-6.36");
}

.o46k1jkal {
  d: path("M65.27 95.49c-3.48.03-7.01-.73-9.87-2.15c-1.43-.71-2.92-1.69-4.06-2.8c-1.16-1.12-2.27-3.13-.92-4.51c1.09-1.11 2.71.01 3.76.58c2.98 1.63 6.4 2.83 9.86 2.98c3.83.17 6.93-1 10.23-2.74c.95-.49 2.81-1.72 3.92-1.04c2.75 1.67-.52 4.68-1.94 5.88c-3.03 2.58-6.96 3.76-10.98 3.8");
}

.t556zx4mp {
  cx: 37.5px;
  cy: 58.24px;
  rx: 7.22px;
  ry: 7.96px;
}

.xthtgwbai {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M64 .39C28.86.39.39 28.87.39 64S28.86 127.61 64 127.61c35.13 0 63.62-28.48 63.62-63.61S99.13.39 64 .39");
}

</style>
