<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_9dmd6jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:24fps-select" /></template>
<style>
.e_9dmd6jb {
  fill: currentColor;
  d: path("M3.846 21.5v-4h1v4zm3.385 0v-4h1v4zm3.385 0v-4h1v4zm3.384 0v-4h6.154v4zm2.808-8.5v-2.5h-3.423V5h1v4.5h2.423V5h1v4.5h1.423v1h-1.423V13zM5.769 13v-2.884q0-.667.475-1.141t1.14-.475H9q.27 0 .442-.173q.173-.173.173-.442v-1.27q0-.269-.173-.442T9 6H5.77V5H9q.666 0 1.14.475q.476.474.476 1.14v1.27q0 .666-.475 1.14Q9.666 9.5 9 9.5H7.384q-.269 0-.442.173t-.173.443V12h3.616v1z");
}

</style>
