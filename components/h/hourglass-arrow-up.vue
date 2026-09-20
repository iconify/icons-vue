<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ta8_3w49a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hourglass-arrow-up" /></template>
<style>
.ta8_3w49a {
  fill: currentColor;
  d: path("M3.5 19v-1H5v-2.654q0-1.184.7-2.123T7.508 12q-1.127-.285-1.817-1.233Q5 9.82 5 8.616V6H3.5V5h10.385v1h-1.462v2.616q0 1.223-.71 2.161q-.71.939-1.836 1.223q1.127.285 1.837 1.214q.709.928.709 2.132V18h1.462v1zm15.385 0V6.916L17.4 8.4l-.708-.708L19.385 5l2.692 2.692l-.713.708l-1.48-1.479V19z");
}

</style>
