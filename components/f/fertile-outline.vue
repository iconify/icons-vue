<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvj2k16ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fertile-outline" /></template>
<style>
.tvj2k16ts {
  fill: currentColor;
  d: path("M8.493 20.291q-1.643-.708-2.859-1.923T3.709 15.51T3 12V4.5l5.275 3.967q.852-1.31 1.791-2.55q.94-1.24 1.934-2.398q.894 1.039 1.842 2.288t1.858 2.66L21 4.5V12q0 1.868-.708 3.51t-1.924 2.858t-2.856 1.923t-3.509.709t-3.51-.709m9.182-2.616Q20 15.35 20 12V6.5l-4.6 3.45q-1.125-1.8-1.825-2.85T12 5q-.875 1.075-1.625 2.175T8.6 9.95L4 6.5V12q0 3.35 2.325 5.675T12 20t5.675-2.325M12 12.5");
}

</style>
