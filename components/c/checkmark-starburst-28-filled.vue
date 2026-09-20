<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="mjsomh_hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-starburst-28-filled" /></template>
<style>
.mjsomh_hl {
  fill: currentColor;
  d: path("M15.722 2.403a3.75 3.75 0 0 1 5.259 2.179l.246.751a2.25 2.25 0 0 0 1.438 1.438l.751.246a3.75 3.75 0 0 1 2.178 5.258l-.358.705a2.25 2.25 0 0 0 0 2.034l.358.705a3.75 3.75 0 0 1-2.178 5.259l-.751.246a2.25 2.25 0 0 0-1.438 1.438l-.247.751a3.75 3.75 0 0 1-5.258 2.178l-.705-.358a2.25 2.25 0 0 0-2.034 0l-.705.358a3.75 3.75 0 0 1-5.258-2.178l-.247-.75a2.25 2.25 0 0 0-1.437-1.44l-.751-.245a3.75 3.75 0 0 1-2.179-5.26l.358-.704a2.25 2.25 0 0 0 0-2.033l-.358-.706a3.75 3.75 0 0 1 2.179-5.258l.75-.247a2.25 2.25 0 0 0 1.438-1.437l.247-.751a3.75 3.75 0 0 1 5.258-2.179l.705.358a2.25 2.25 0 0 0 2.034 0zm3.808 7.817a.75.75 0 0 0-1.06 0l-5.97 5.97l-2.97-2.97a.75.75 0 0 0-1.06 1.06l3.5 3.5a.75.75 0 0 0 1.06 0l6.5-6.5a.75.75 0 0 0 0-1.06");
}

</style>
