<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrd16b9tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:compass-calibration-outline-sharp" /></template>
<style>
.rrd16b9tr {
  fill: currentColor;
  d: path("M9.165 19.22Q8 18.056 8 16.385t1.165-2.836T12 12.385t2.836 1.164T16 16.384q0 1.672-1.164 2.836Q13.67 20.385 12 20.385T9.165 19.22m4.96-.71q.875-.876.875-2.126t-.875-2.125T12 13.385t-2.125.875T9 16.385t.875 2.125t2.125.875t2.125-.875m-7.086-7.09L3.462 7.804Q5.25 6.265 7.443 5.44Q9.637 4.616 12 4.616t4.557.825q2.193.825 3.982 2.364l-3.578 3.615q-1.044-.871-2.319-1.337T12 9.616t-2.642.466t-2.32 1.337m.112-1.303q1.05-.75 2.287-1.125T12 8.616t2.538.362t2.312 1.088l2.2-2.2q-1.55-1.1-3.338-1.675T12 5.616t-3.713.575T4.95 7.866zM12 16.385");
}

</style>
