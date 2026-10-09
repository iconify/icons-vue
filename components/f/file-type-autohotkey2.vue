<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="zujmrdjng"><path class="k82ipg7cc"/><path class="g-fjc04gm"/><path class="g_qko5b4k"/></g><g class="yw4xr_bje"><path class="rhce20lps"/><path class="v8h7t5bjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-autohotkey2" /></template>
<style>
.g_qko5b4k {
  d: path("M10.75 2h14.87C28 2 30 4.2 30 6.37v14.88c0 4.44-4.31 8.75-8.75 8.75H6.37A4.53 4.53 0 0 1 2 25.62V10.75C2 6.31 6.31 2 10.75 2");
}

.g-fjc04gm {
  d: path("M10.75 2C6.31 2 2 6.31 2 10.75v14.87A4.53 4.53 0 0 0 6.37 30h14.88c4.44 0 8.75-4.31 8.75-8.75V6.37C30 4.2 28 2 25.62 2zm-.7 4.4c.68 0 1.14.15 1.14 1.04v7.24l8.75-1.2V9.05c0-1.29.97-2.63 2.18-2.63s2.2-.27 2.2 1.02v15.6c0 1.3-.98 2.63-2.2 2.63c-1.2 0-2.18.28-2.18-1v-6.81l-8.75 1.2v3.99c0 1.29-.98 2.62-2.19 2.62s-2.19.28-2.19-1V9.04c0-1.29.98-2.63 2.19-2.63z");
}

.k82ipg7cc {
  d: path("M10.75 2C6.31 2 2 6.31 2 10.75v14.87A4.53 4.53 0 0 0 6.37 30h14.88c4.44 0 8.75-4.31 8.75-8.75V6.37C30 4.2 28 2 25.62 2zm-.7 4.37c.68.01 1.14.16 1.14 1.04v15.61c0 1.3-.98 2.63-2.19 2.63s-2.19.27-2.19-1.01V9.02C6.81 7.74 7.8 6.4 9 6.4l1.04-.03m13.12 0c.68.01 1.14.16 1.14 1.04v15.61c0 1.3-.97 2.63-2.19 2.63s-2.18.27-2.18-1.01V9.02c0-1.28.97-2.62 2.18-2.62z");
}

.rhce20lps {
  d: path("M9 6.4c1.21 0 2.19-.28 2.19 1.01v15.61c0 1.3-.98 2.63-2.19 2.63s-2.19.27-2.19-1.01V9.02C6.81 7.74 7.8 6.4 9 6.4m13.12 0c1.22 0 2.2-.28 2.2 1.01v15.61c0 1.3-.98 2.63-2.2 2.63s-2.18.27-2.18-1.01V9.02c0-1.28.97-2.62 2.18-2.62");
}

.v8h7t5bjq {
  d: path("m10.75 14.71l9.62-1.31v4.37l-9.62 1.32z");
}

.yw4xr_bje {
  fill: var(--svg-color--8cf287, #8cf287);
}

.zujmrdjng {
  fill: var(--svg-color--448e3a, #448e3a);
  stroke-width: var(--svg-stroke-width--0-26px, 0.26px);
}

</style>
