<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf9mk5bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heart-half" /></template>
<style>
.pf9mk5bcs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 6.714v11.901q1.617-1.123 3.239-2.633q4.261-3.965 4.261-7.232q0-4-4-4q-2.23 0-3.5 1.964m-.359 13.926q-.088.054-.188.082q-.099.028-.203.028t-.203-.028t-.188-.082q-2.315-1.414-4.62-3.56Q2.25 12.67 2.25 8.75q0-2.298 1.601-3.899T7.75 3.25q2.621 0 4.25 1.953q1.629-1.953 4.25-1.953q2.298 0 3.899 1.601T21.75 8.75q0 3.92-4.739 8.33q-2.305 2.146-4.62 3.56");
}

</style>
