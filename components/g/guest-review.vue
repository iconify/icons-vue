<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq9yu132l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:guest-review" /></template>
<style>
.qq9yu132l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.202 3.202Q2.25 4.154 2.25 5.5v10q0 3.25 3.25 3.25h.75v2.75q0 .136.048.264q.048.127.138.23q.098.112.232.178q.133.066.282.076t.29-.038q.142-.047.254-.146l3.788-3.314H18.5q1.346 0 2.298-.952t.952-2.298v-10q0-1.346-.952-2.298T18.5 2.25h-13q-1.346 0-2.298.952M13.26 7.359l.001.002l.238.482q.175.353.565.41l.534.078q.865.125 1.135.956q.27.832-.357 1.442l-.385.376q-.283.275-.217.664l.092.53q.149.862-.559 1.376q-.707.514-1.481.106l-.477-.25q-.349-.184-.698 0l-.478.251q-.773.407-1.48-.107q-.708-.514-.559-1.376l.092-.532q.066-.387-.216-.662l-.387-.377q-.626-.609-.356-1.441q.27-.831 1.136-.956l.533-.078q.39-.057.565-.41l.239-.484q.384-.784 1.26-.784q.875 0 1.26.784");
}

</style>
