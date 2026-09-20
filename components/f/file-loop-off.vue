<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g clip-rule="evenodd" class="d2kvgvbvc"><path class="vk260c0wl"/><path class="ep84igb8a"/></g><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:file-loop-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.ep84igb8a {
  d: path("M8.049 8.678a2.193 2.193 0 1 0-2.058 3.873a2.193 2.193 0 0 0 2.058-3.873m-4.732-.031a4.193 4.193 0 1 1 2.674 6.033l-1.676 3.155a1 1 0 0 1-1.767-.938l1.677-3.155a4.195 4.195 0 0 1-.908-5.095");
}

.vk260c0wl {
  d: path("M5 4a2.5 2.5 0 0 1 2.5-2.5h5.1a1 1 0 0 1 .702.288l4.4 4.333a1 1 0 0 1 .298.712V14a2.5 2.5 0 0 1-2.5 2.5H9a1 1 0 1 1 0-2h6.5a.5.5 0 0 0 .5-.5V7.833h-2.4a2 2 0 0 1-2-2V3.5H7.5A.5.5 0 0 0 7 4v1.5a1 1 0 0 1-2 0zm8.6.888l.96.945h-.96z");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
