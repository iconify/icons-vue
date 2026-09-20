<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do-qup_at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:deployed-code-history-sharp" /></template>
<style>
.do-qup_at {
  fill: currentColor;
  d: path("M18.385 18.646v-2.723h-.77v3.046l2.035 2.035l.546-.546zM12 11.427L5.575 7.714l-.556.298v.511L12 12.573l7-4.05v-.512l-.575-.297zm-8 5.121V7.452l8-4.598l8 4.598v5.242q-.483-.171-.976-.25T18 12.365q-2.65 0-4.517 1.868t-1.867 4.517q0 .483.067.95t.22.914l.193.594zm11.165 5.038Q14 20.42 14 18.75t1.165-2.835T18 14.75t2.836 1.165T22 18.75t-1.164 2.836T18 22.75t-2.835-1.164");
}

</style>
