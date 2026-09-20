<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vheaj0zhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:biotech-sharp" /></template>
<style>
.vheaj0zhd {
  fill: currentColor;
  d: path("M5.885 20.5v-1h5v-3h-.5q-1.864 0-3.182-1.318T5.885 12q0-1.31.677-2.404t1.875-1.623q-.023.28.037.527t.168.49q-.825.439-1.291 1.246q-.466.808-.466 1.764q0 1.462 1.019 2.48t2.48 1.02h7.5v1h-5.768v3h6v1zm8.654-8.9l-.339-.95l-.95.389l-.52-1.441q.309-.323.459-.732q.15-.408.15-.866q0-.906-.585-1.593q-.585-.688-1.477-.823l-.508-1.403l.95-.35l-.35-.939l1.17-.43l.338.95l.873-.312l2.48 6.77l-.872.35l.35.95zM9.696 9.189Q9.2 8.692 9.2 8t.496-1.188t1.189-.497q.692 0 1.188.496q.496.497.496 1.189t-.496 1.189q-.496.495-1.188.495q-.693 0-1.189-.495");
}

</style>
