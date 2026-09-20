<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyfut8b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:invert-colors-sharp" /></template>
<style>
.eyfut8b0s {
  fill: currentColor;
  d: path("M12 21q-3.325 0-5.663-2.3T4 13.125q0-1.65.625-3.062T6.35 7.55L12 2l5.65 5.55q1.1 1.1 1.725 2.513T20 13.125q0 3.275-2.337 5.575T12 21m0-2V4.8L7.75 9q-.875.825-1.312 1.875T6 13.125q0 2.425 1.75 4.15T12 19");
}

</style>
