<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1vjqd8fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chart-contour" /></template>
<style>
.m1vjqd8fu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.921 1.754q2.996-.331 6.374 1.734q1.801 1.101 2.828 1.272q2.668.445 3.06 3.97q.324 2.919-1.002 5.585q-.374.88-.784 2.541q-1.123 4.554-5.25 5.379q-3.25.723-7.782-1.843q-1.775-1.005-2.502-1.154q-2.583-.439-3.102-3.422q-.397-2.281.527-5.053q.102-.304.311-.975q2.349-7.534 7.322-8.034m5.685 4.916q-2.231-1.611-4.181-1.416l-.018.002q-3.021.377-4.338 3.428q-1.682 3.38-.22 5.938q2.295 4.017 6.219 3.625q2.862-.26 4.533-3.753q.201-.42.311-.641q.924-1.627.869-3.376q-.069-2.202-1.736-2.916q-.507-.218-1.439-.891");
}

</style>
