<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zf5zqkcas"/><g class="b_3pvcbgt"><path class="e67cpjbkb"/><path class="te4t4jbll"/><path class="py3pqrxye"/><path class="x1qlbptmq"/><path class="twq_zub7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-vapor" /></template>
<style>
.b_3pvcbgt {
  fill: var(--svg-color--25c4f2, #25c4f2);
}

.e67cpjbkb {
  fill-opacity: var(--svg-fill-opacity--0-22, 0.22);
  d: path("M7.22 16H16l-4.39 9.15z");
}

.py3pqrxye {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 16H7.22l4.4-9.15zm8.78 0H16l4.4-9.15z");
}

.te4t4jbll {
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 16h8.78l-4.39 9.15z");
}

.twq_zub7j {
  d: path("M29.17 6.01h-8.78a.8.8 0 0 0-.75.48L16 14.08l-3.64-7.6a.8.8 0 0 0-.75-.47H2.83a.83.83 0 0 0-.75 1.2l8.78 18.3a.8.8 0 0 0 .75.48h8.78a.8.8 0 0 0 .75-.48l8.78-18.3a.83.83 0 0 0-.75-1.2M11.6 8.77l3.07 6.4H8.55zm-7.45-1.1h6.13l-3.07 6.4zm7.45 15.56l-3.07-6.4h6.14zm1.33 1.1l3.06-6.4l3.07 6.4zm7.45-1.1l-3.07-6.4h6.14zm-3.07-8.06l3.07-6.4l3.07 6.4zm7.46-1.1l-3.07-6.4h6.14z");
}

.x1qlbptmq {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M20.4 25.15h-8.8L16 16z");
}

.zf5zqkcas {
  fill: var(--svg-color--e9f9fd, #e9f9fd);
  fill-opacity: var(--svg-fill-opacity--0-1, 0.1);
  d: path("M2.83 6.85h8.79L7.22 16zm17.56 0h8.78L24.78 16z");
}

</style>
