<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rl6nndbmv"/><path class="r7w0uv6gg"/><path class="khzmos1ot"/><g class="n1mjunbsu"><path class="g_26z5j6e"/><circle class="j9l0slmri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:japanese-symbol-for-beginner" /></template>
<style>
.g_26z5j6e {
  d: path("M73.57 42.02c1.71-.87 20.91-15.79 20.91-15.79s2.89-1.97 1.43-4.5c-1.4-2.44-4.09-1.73-5.55-.67S73.19 34.01 71.85 35.23c-1.4 1.14-1.88 3.71-1.29 5.38c.6 1.67 1.76 2.07 3.01 1.41");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.j9l0slmri {
  cx: 100.61px;
  cy: 16.97px;
  r: 3.3px;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.khzmos1ot {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.75 19.81c1.4 1.32 29.03 21.24 29.03 21.24s2.83 2.06 4.72-.17c1.83-2.14.25-4.43-1.24-5.45s-25.1-18.67-26.7-19.53c-1.54-.93-4.13-.52-5.5.6s-1.35 2.35-.31 3.31");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.r7w0uv6gg {
  fill: var(--svg-color--26a69a, #26a69a);
  d: path("M105.5 4.88L66.5 34c-.73.58-1.61.88-2.5.88V124c.88 0 1.77-.29 2.5-.88l44-29.92c.95-.76 1.5-1.91 1.5-3.12V8.01c0-3.36-3.88-5.22-6.5-3.13");
}

.rl6nndbmv {
  fill: var(--svg-color--fce438, #fce438);
  d: path("m61.5 34l-39-29.12C19.88 2.79 16 4.65 16 8.01v82.07c0 1.22.55 2.36 1.5 3.12l44 29.92c.73.58 1.61.88 2.5.88V34.88c-.88 0-1.77-.29-2.5-.88");
}

</style>
