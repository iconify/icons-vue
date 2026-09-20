<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwtcwtiyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:church-outline-sharp" /></template>
<style>
.jwtcwtiyf {
  fill: currentColor;
  d: path("M2 22v-8l4-1.775V9l5-2.5V5H9V3h2V1h2v2h2v2h-2v1.5L18 9v3.225L22 14v8h-9v-5h-2v5zm2-2h5v-5.1h6V20h5v-4.8l-4-1.8v-3.35L12 8l-4 2.05v3.35l-4 1.8zm9.063-6.937q.437-.438.437-1.063t-.437-1.062T12 10.5t-1.062.438T10.5 12t.438 1.063T12 13.5t1.063-.437M12 14");
}

</style>
