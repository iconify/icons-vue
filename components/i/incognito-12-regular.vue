<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="v17pmhbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:incognito-12-regular" /></template>
<style>
.v17pmhbkp {
  fill: currentColor;
  d: path("M8.75 6.5A2.25 2.25 0 1 1 6.515 9h-1.03a2.25 2.25 0 1 1-.116-1h1.262A2.25 2.25 0 0 1 8.75 6.5m-5.5 1a1.25 1.25 0 1 0 0 2.5a1.25 1.25 0 0 0 0-2.5m5.5 0a1.25 1.25 0 1 0 0 2.5a1.25 1.25 0 0 0 0-2.5M6 4c1.257 0 2.408.128 3.244.256a17 17 0 0 1 1.372.258h.002a.5.5 0 0 1-.237.971h-.003q-.167-.04-.336-.073A21 21 0 0 0 6 5a21 21 0 0 0-4.042.412q-.169.034-.336.072l-.003.001a.5.5 0 0 1-.237-.97l.002-.001s.252-.057.375-.082A22 22 0 0 1 6 4m1.383-3a1.5 1.5 0 0 1 1.342.83l.722 1.447a.5.5 0 1 1-.893.447L7.83 2.276A.5.5 0 0 0 7.383 2H4.619a.5.5 0 0 0-.447.276l-.725 1.448a.5.5 0 0 1-.893-.447l.723-1.448A1.5 1.5 0 0 1 4.62 1z");
}

</style>
