<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo751pb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:jo-staff" /></template>
<style>
.eo751pb3d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m20.485 3.869l-.354-.355q-1.767-1.765-3.534.001q-.733.732-.733 1.768q0 .775.411 1.381l-9.611 9.611q-.606-.411-1.382-.411q-1.035 0-1.768.733q-1.765 1.767.001 3.534l.354.355q1.767 1.765 3.534-.001q.733-.732.733-1.768q0-.775-.411-1.381l9.611-9.611q.606.411 1.381.411q1.036 0 1.769-.733q1.765-1.767-.001-3.534");
}

</style>
