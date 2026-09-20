<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf1qa7bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:how-to-reg-outline" /></template>
<style>
.cf1qa7bdm {
  fill: currentColor;
  d: path("M2 20v-2.8q0-.825.425-1.55t1.175-1.1q1.275-.65 2.875-1.1T10 13q.75 0 1.463.075t1.387.225l-1.75 1.75q-.275-.05-.537-.05H10q-1.775 0-3.187.425T4.5 16.35q-.225.125-.363.35T4 17.2v.8h6.25l2 2zm13.55.4l-3.45-3.45l1.4-1.4l2.05 2.05l5.05-5.05l1.4 1.4zm-8.375-9.575Q6 9.65 6 8t1.175-2.825T10 4t2.825 1.175T14 8t-1.175 2.825T10 12t-2.825-1.175m4.238-1.412Q12 8.825 12 8t-.587-1.412T10 6t-1.412.588T8 8t.588 1.413T10 10t1.413-.587M10 8");
}

</style>
