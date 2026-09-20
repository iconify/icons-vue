<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxtbp199i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:info-i-outline-sharp" /></template>
<style>
.pxtbp199i {
  fill: currentColor;
  d: path("M10.588 6.413Q10 5.825 10 5t.588-1.412T12 3t1.413.588T14 5t-.587 1.413T12 7t-1.412-.587M10.5 21V9h3v12z");
}

</style>
