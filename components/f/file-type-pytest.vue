<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zlwfcobrf"/><path class="ufg6enbjh"/><path class="j4wk0db4u"/><path class="hlaihfbmz"/><path class="g7uw6acei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-pytest" /></template>
<style>
.g7uw6acei {
  fill: var(--svg-color--df2815, #df2815);
  d: path("M22.45 2h4.48v1.03h-4.48zm0 5.53h4.48v7.58h-4.48z");
}

.hlaihfbmz {
  fill: var(--svg-color--f07e16, #f07e16);
  d: path("M16.7 2h4.47v1.03H16.7zm0 5.53h4.48v12.31H16.7z");
}

.j4wk0db4u {
  fill: var(--svg-color--c7d302, #c7d302);
  d: path("M10.91 2h4.48v1.03h-4.48zm0 5.53h4.48v18.44h-4.48z");
}

.ufg6enbjh {
  fill: var(--svg-color--009fe3, #009fe3);
  d: path("M5.05 2h4.48v1.03H5.05zm0 5.53h4.48V30H5.05z");
}

.zlwfcobrf {
  fill: var(--svg-color--696969, #696969);
  d: path("M4.86 4.21h22.28a1.1 1.1 0 1 1 0 2.19H4.86a1.1 1.1 0 0 1 0-2.19");
}

</style>
