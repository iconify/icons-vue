<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3nhs11_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:confirmation-number-sharp" /></template>
<style>
.f3nhs11_x {
  fill: currentColor;
  d: path("M12 17q.425 0 .713-.288T13 16t-.288-.712T12 15t-.712.288T11 16t.288.713T12 17m0-4q.425 0 .713-.288T13 12t-.288-.712T12 11t-.712.288T11 12t.288.713T12 13m0-4q.425 0 .713-.288T13 8t-.288-.712T12 7t-.712.288T11 8t.288.713T12 9M2 20v-6q.825 0 1.413-.587T4 12t-.587-1.412T2 10V4h20v6q-.825 0-1.412.588T20 12t.588 1.413T22 14v6z");
}

</style>
