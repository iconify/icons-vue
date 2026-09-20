<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvs-khgcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ink-pen-outline" /></template>
<style>
.rvs-khgcf {
  fill: currentColor;
  d: path("m12.25 10.825l.925.925L18.6 6.325l-.925-.925zM5 19h.925l5.825-5.825l-.925-.925L5 18.075zm8.875-5.125l-3.75-3.75L14.3 5.95l-.725-.725L8.1 10.7L6.7 9.3l5.45-5.475q.6-.6 1.413-.6t1.412.6l.725.725l1.25-1.25q.3-.3.713-.3t.712.3L20.7 5.625q.3.3.3.712t-.3.713zM6.75 21H3v-3.75l7.125-7.125l3.75 3.75z");
}

</style>
