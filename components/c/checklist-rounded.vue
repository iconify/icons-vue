<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3z25vb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:checklist-rounded" /></template>
<style>
.c3z25vb2l {
  fill: currentColor;
  d: path("m5.525 16.175l3.55-3.55q.3-.3.7-.288t.7.313q.275.3.275.7t-.275.7L6.25 18.3q-.3.3-.7.3t-.7-.3L2.7 16.15q-.275-.275-.275-.7t.275-.7t.7-.275t.7.275zm0-8l3.55-3.55q.3-.3.7-.288t.7.313q.275.3.275.7t-.275.7L6.25 10.3q-.3.3-.7.3t-.7-.3L2.7 8.15q-.275-.275-.275-.7t.275-.7t.7-.275t.7.275zM14 17q-.425 0-.712-.288T13 16t.288-.712T14 15h7q.425 0 .713.288T22 16t-.288.713T21 17zm0-8q-.425 0-.712-.288T13 8t.288-.712T14 7h7q.425 0 .713.288T22 8t-.288.713T21 9z");
}

</style>
