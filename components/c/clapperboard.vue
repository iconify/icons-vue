<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="sgtu7yuar"/><path class="c6uageb_z"/><path class="yj_ury1ar"/><path class="new2gq-mz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:clapperboard" /></template>
<style>
.c6uageb_z {
  d: path("M9.935 7.698L7.339 5.195l1.389-1.44l2.595 2.503zm-3.908.855L3.432 6.05L4.82 4.61l2.595 2.504zm7.815-1.711L11.247 4.34l1.388-1.44l2.595 2.504zm-4.01 5.713l2-3l-1.664-1.11l-2 3zm4 0l2-3l-1.664-1.11l-2 3zm-8 0l2-3l-1.664-1.11l-2 3z");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.new2gq-mz {
  d: path("M18 13H2v-2h16z");
}

.sgtu7yuar {
  d: path("M.707 6.08a1 1 0 0 1 .763-1.192L16.123 1.68a1 1 0 0 1 1.19.763l.642 2.93a1 1 0 0 1-.763 1.192L2.54 9.773a1 1 0 0 1-1.19-.763zm2.168.548l.213.977l12.7-2.78l-.214-.977z");
}

.yj_ury1ar {
  d: path("M1.5 9a1 1 0 0 1 1-1h15a1 1 0 0 1 1 1v9a1 1 0 0 1-1 1h-15a1 1 0 0 1-1-1zm2 1v7h13v-7z");
}

</style>
