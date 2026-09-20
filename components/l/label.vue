<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="w_x82kras"/><path class="wd8njbc4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:label" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.w_x82kras {
  fill-rule: evenodd;
  d: path("M4.91 4.564c-.018.283-.034.596-.047.927c-.054 1.358-.047 2.907.102 4.078l7.265 7.265l4.95-4.95l-7.265-7.265c-1.17-.149-2.72-.156-4.078-.102c-.331.013-.643.03-.927.047M3.094 2.748c-.097.092-.49 4.567-.077 7.33c.044.294.189.56.399.77l7.753 7.754a1.5 1.5 0 0 0 2.122 0l5.657-5.657a1.5 1.5 0 0 0 0-2.122L11.194 3.07a1.4 1.4 0 0 0-.77-.4c-2.763-.411-7.238-.02-7.33.078");
}

.wd8njbc4p {
  d: path("M9.142 7.466A1 1 0 1 1 7.727 8.88a1 1 0 0 1 1.415-1.414");
}

</style>
