<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy64dkb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:balloon-animal" /></template>
<style>
.cy64dkb_k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.75 2.75Q15 2.75 15 5.25q0 .224.03.428q-1.53.638-1.53 3.572q0 .677.082 1.232q-1.345-.483-3.082-.483q-2.137 0-3.68.732q-.34.161-.616.34q.046-.374.046-.821q0-2.75-1.75-2.75t-1.75 2.75T4.5 13q.272 0 .501-.066L5 12.999v.002q0 1.199 1.324 2.003q-.574.871-.574 2.746q0 3.5 2 3.5t2-3.5q0-1.051-.18-1.786q.45.037.93.037t.93-.037q-.18.735-.18 1.786q0 3.5 2 3.5t2-3.5q0-1.875-.574-2.746Q16.001 14.2 16 13q2.5 0 2.5-3.75q0-.85-.128-1.507q.184.007.378.007q3.75 0 3.75-2.5t-3.75-2.5");
}

</style>
