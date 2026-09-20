<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a33u2ccfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:biotech-outline-sharp" /></template>
<style>
.a33u2ccfs {
  fill: currentColor;
  d: path("M5.885 20.5v-1h5v-3h-.5q-1.868 0-3.184-1.316T5.885 12q0-1.386.799-2.523q.799-1.136 2.108-1.654q.046-1.023.878-1.586T11.434 6l-.665-1.82l.95-.35l-.35-.938l1.17-.43l.338.95l.873-.312l2.48 6.77l-.872.35l.35.95l-1.17.43l-.338-.95l-.95.389l-.638-1.843q-.298.427-.767.679t-1.006.24q-.627-.011-1.131-.366t-.758-.914q-.944.419-1.505 1.267T6.885 12q0 1.458 1.02 2.48q1.021 1.02 2.48 1.02h7.5v1h-5.77v3h6v1zm7.919-10.642l1.285-.504l-1.854-5.123l-1.335.465zm-2.043-.98q.355-.354.355-.877t-.354-.877t-.876-.355t-.877.354t-.355.876t.353.877t.876.355t.878-.354M10.885 8");
}

</style>
