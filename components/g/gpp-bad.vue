<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aly_b9buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gpp-bad" /></template>
<style>
.aly_b9buk {
  fill: currentColor;
  d: path("m9.9 14.73l2.1-2.1l2.1 2.1l.708-.707l-2.1-2.1l2.1-2.1l-.708-.707l-2.1 2.1l-2.1-2.1l-.708.707l2.1 2.1l-2.1 2.1zm2.1 6.232q-3.014-.895-5.007-3.651T5 11.1V5.692l7-2.615l7 2.615V11.1q0 3.454-1.993 6.21T12 20.963");
}

</style>
