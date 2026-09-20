<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqb2a2bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:clock-arrow-down" /></template>
<style>
.fqb2a2bfv {
  fill: currentColor;
  d: path("M4.207 16.438q-1.86-1.87-1.86-4.534t1.86-4.534T8.73 5.5t4.534 1.87t1.87 4.534t-1.87 4.534t-4.534 1.87t-4.524-1.87M19.385 19l-2.693-2.692l.714-.708l1.479 1.479V5h1v12.085l1.484-1.485l.708.708zm-8.346-4.02l.727-.707l-2.516-2.54v-3.54h-1v4z");
}

</style>
