<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuruerb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:heart-smile" /></template>
<style>
.wuruerb7l {
  fill: currentColor;
  d: path("M14.348 14.227q1.042-.773 1.45-2.035l-1.056.02q-.358.829-1.098 1.308T12 14t-1.644-.48t-1.098-1.308H8.202q.408 1.261 1.45 2.025Q10.694 15 12 15t2.348-.773M9.81 9.811q.229-.228.229-.561t-.228-.56t-.561-.228t-.56.228t-.228.56t.228.56q.227.229.56.229t.56-.228m5.5 0q.229-.228.229-.561t-.228-.56t-.561-.228t-.56.228t-.228.56t.228.56q.227.229.56.229t.56-.228M12 20l-.758-.673q-2.448-2.22-4.05-3.81T4.664 12.71t-1.296-2.196T3 8.52q0-1.927 1.296-3.223T7.5 4q1.32 0 2.475.675T12 6.639q.87-1.289 2.025-1.964T16.5 4q1.908 0 3.204 1.296T21 8.52q0 1.015-.368 1.994q-.369.98-1.296 2.197q-.926 1.217-2.519 2.807t-4.06 3.81z");
}

</style>
