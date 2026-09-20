<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7-ov2u7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:info-i-outline-rounded" /></template>
<style>
.q7-ov2u7l {
  fill: currentColor;
  d: path("M10.588 6.413Q10 5.825 10 5t.588-1.412T12 3t1.413.588T14 5t-.587 1.413T12 7t-1.412-.587m.35 14.15q-.438-.438-.438-1.063v-9q0-.625.438-1.062T12 9t1.063.438t.437 1.062v9q0 .625-.437 1.063T12 21t-1.062-.437");
}

</style>
