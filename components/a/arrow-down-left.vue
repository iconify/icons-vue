<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="sdu_4tboo"/><path class="c42-c9tbz"/><path class="jqji2jc1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:arrow-down-left" /></template>
<style>
.c42-c9tbz {
  d: path("M5.903 7.354a1 1 0 0 1 1.086.906l.471 5.185a1 1 0 1 1-1.991.181l-.472-5.185a1 1 0 0 1 .906-1.087");
}

.jqji2jc1x {
  d: path("M7.172 12.829a1 1 0 0 1 0-1.415l5.656-5.656a1 1 0 1 1 1.415 1.414l-5.657 5.657a1 1 0 0 1-1.414 0");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.sdu_4tboo {
  d: path("M12.646 14.098a1 1 0 0 1-1.087.905l-5.185-.472a1 1 0 1 1 .181-1.991l5.186.471a1 1 0 0 1 .905 1.087");
}

</style>
