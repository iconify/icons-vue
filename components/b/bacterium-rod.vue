<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5eeweqch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bacterium-rod" /></template>
<style>
.d5eeweqch {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.249 10.137q.695 1.065.695 2.419q0 1.863-1.318 3.181l-3.889 3.889q-1.318 1.318-3.182 1.318t-3.181-1.318q-1.318-1.318-1.318-3.181q0-1.864 1.318-3.182l3.889-3.889q1.318-1.318 3.182-1.318q1.567 0 2.748.932q.599-.209.806-1.21q.393-1.899 1.819-2.256q.595-.148.965-1.212q.65-1.87 2.124-2.054q.183-.025.503-.05q.415-.033.419-.041q.033-.066.079-.125q.045-.058.101-.107q.055-.048.12-.085q.064-.036.134-.06q.07-.023.143-.032t.147-.004t.145.025t.137.052q.134.067.232.18q.097.112.145.254q.047.141.036.29q-.01.149-.077.282q-.383.767-1.643.866q-.28.023-.435.043q-.549.069-.893 1.059q-.636 1.829-2.018 2.175q-.512.128-.714 1.104q-.301 1.453-1.219 2.055");
}

</style>
