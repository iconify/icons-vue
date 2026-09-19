<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h16ni_bzm"/><path class="ydi9sccjs"/><path class="yu-x0pm6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:battlelands" /></template>
<style>
.h16ni_bzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.172 20.952l20.717-4.362l1.513 7.185l-20.718 4.362z");
}

.ydi9sccjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.503 19.507l8.323-1.752l.674 3.2l-8.323 1.753zm-.614-2.917l-.589-2.798l-2.303 3.407M18.66 33.64l-2.697.568l-1.278-6.07l4.025-.848z");
}

.yu-x0pm6m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.993 30.31l3.271-1.398l3.432-.723l-1.524-7.237l-6.846 1.442zM4.5 22.778l1.826-.384l1.666 7.916l-1.826.384zm8.082-4.623l2.013-.424l.59 2.798l-2.014.423z");
}

</style>
