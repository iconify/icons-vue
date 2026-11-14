<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tekoncrou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:genre-acoustic" /></template>
<style>
.tekoncrou {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q1.036 0 1.768.732T14.5 4.25t-.732 1.768q-.452.451-1.018.624v2.13q4.5.275 4.5 3.978q0 .812-.451 1.678q2.451 1.359 2.451 3.822q0 4-7.25 4t-7.25-4q0-2.463 2.451-3.822q-.451-.866-.451-1.678q0-3.703 4.5-3.978V6.683Q9.5 6.342 9.5 4.25q0-2.5 2.5-2.5M9.5 17q0 2.5 2.5 2.5q1.036 0 1.768-.732T14.5 17t-.732-1.768T12 14.5q-2.5 0-2.5 2.5");
}

</style>
