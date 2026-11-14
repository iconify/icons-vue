<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytbrslblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chat-star" /></template>
<style>
.ytbrslblh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 2.75Q3.25 2.75 3.25 6v8q0 3.122 3 3.245V20q0 .136.048.264q.048.127.138.23q.098.112.232.178q.133.066.282.076t.29-.038q.142-.047.254-.146l3.788-3.314H17.5q3.25 0 3.25-3.25V6q0-3.25-3.25-3.25zm6.76 4.109l.001.002l.238.482q.175.353.565.41l.534.078q.865.125 1.135.956q.27.832-.357 1.442l-.385.376q-.283.275-.217.664l.092.53q.149.862-.559 1.376q-.707.514-1.481.106l-.477-.25q-.349-.184-.698 0l-.478.251q-.773.407-1.48-.107q-.708-.514-.559-1.376l.092-.532q.066-.387-.216-.662l-.387-.377q-.626-.609-.356-1.441q.27-.831 1.136-.956l.533-.078q.39-.057.565-.41l.239-.484q.384-.784 1.26-.784q.875 0 1.26.784");
}

</style>
