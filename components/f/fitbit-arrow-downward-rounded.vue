<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b59de05uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fitbit-arrow-downward-rounded" /></template>
<style>
.b59de05uc {
  fill: currentColor;
  d: path("M11 14.175V7q0-.425.288-.713T12 6q.425 0 .713.288T13 7v7.175l2.9-2.875q.275-.275.688-.288t.712.288q.275.275.275.7t-.275.7l-4.6 4.6q-.3.3-.7.3t-.7-.3l-4.6-4.6q-.275-.275-.288-.687T6.7 11.3q.275-.275.7-.275t.7.275l2.9 2.875Z");
}

</style>
