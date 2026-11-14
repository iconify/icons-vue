<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdf22s-9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:jet-engine-front" /></template>
<style>
.kdf22s-9g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M12 14.667q-.774 1.489-2.276 2.278q-2.838 1.49-4.367-1.059q-1.528-2.648 1.173-4.397q1.421-.92 3.1-.847q-.891-1.402-.817-3.112Q8.956 4.25 12 4.25t3.187 3.28q.074 1.71-.817 3.112q1.679-.073 3.1.847q2.701 1.749 1.18 4.386q-1.536 2.56-4.374 1.07q-1.502-.789-2.276-2.278");
}

</style>
