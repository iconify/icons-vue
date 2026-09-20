<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qutia1ink"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:fire-extinguisher-bold" /></template>
<style>
.qutia1ink {
  fill: currentColor;
  d: path("M219.45 44.51L170.07 29.7L185 22.93a12 12 0 1 0-10-21.85l-41.78 19A84.09 84.09 0 0 0 52 104v104a12 12 0 0 0 24 0v-28h16v52a20 20 0 0 0 20 20h48a20 20 0 0 0 20-20V104a44.08 44.08 0 0 0-32-42.32V48.13l64.55 19.37a11.8 11.8 0 0 0 3.45.5a12 12 0 0 0 3.45-23.49M76 156v-52a60.1 60.1 0 0 1 48-58.79v16.47A44.06 44.06 0 0 0 92 104v52Zm40 72v-48h40v48Zm40-124v52h-40v-52a20 20 0 0 1 40 0");
}

</style>
