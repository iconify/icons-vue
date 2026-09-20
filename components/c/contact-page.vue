<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6t321aie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:contact-page" /></template>
<style>
.c6t321aie {
  fill: currentColor;
  d: path("M12 14q.825 0 1.413-.587T14 12t-.587-1.412T12 10t-1.412.588T10 12t.588 1.413T12 14m-4 4h8v-.575q0-.6-.325-1.1t-.9-.75q-.65-.275-1.338-.425T12 15t-1.437.15t-1.338.425q-.575.25-.9.75T8 17.425zm10 4H6q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h8l6 6v12q0 .825-.587 1.413T18 22");
}

</style>
