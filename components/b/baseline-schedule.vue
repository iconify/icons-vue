<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqa-9soic"/><path class="gp0o37bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-schedule" /></template>
<style>
.gp0o37bde {
  fill: currentColor;
  d: path("M12.5 7H11v6l5.25 3.15l.75-1.23l-4.5-2.67z");
}

.nqa-9soic {
  fill: currentColor;
  d: path("M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2M12 20c-4.42 0-8-3.58-8-8s3.58-8 8-8s8 3.58 8 8s-3.58 8-8 8");
}

</style>
