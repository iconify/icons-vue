<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npsaehb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lyrics" /></template>
<style>
.npsaehb2d {
  fill: currentColor;
  d: path("M7.077 13.5h3v-1h-3zm9.77-2.729q-.732-.728-.732-1.769t.73-1.771q.729-.731 1.77-.731q.438 0 .815.156q.378.156.686.442V1.5h3v1h-2V9q0 1.042-.729 1.77q-.729.73-1.77.73t-1.77-.728m-9.77-.272h6v-1h-6zm0-3h6v-1h-6zM6.154 17l-2.577 2.577V4.616q0-.667.475-1.141T5.192 3h9.77q.666 0 1.14.475t.475 1.14v.252q-1.183.581-1.88 1.694T14 9t.697 2.44t1.88 1.693v2.252q0 .666-.475 1.14t-1.14.475z");
}

</style>
