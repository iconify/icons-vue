<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecar5fbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:detector-sharp" /></template>
<style>
.ecar5fbmp {
  fill: currentColor;
  d: path("M8.297 19.32q-1.772-.681-3.226-1.968l.714-.713q1.294 1.159 2.896 1.76t3.344.601q1.723 0 3.322-.588q1.6-.589 2.894-1.73l.707.69q-1.46 1.286-3.238 1.957Q13.93 20 12 20t-3.703-.68M12 16.23q-1.17 0-2.252-.409q-1.082-.41-1.967-1.16l.707-.707q.745.629 1.657.953t1.874.324t1.865-.324t1.647-.953l.708.707q-.904.77-1.977 1.17t-2.262.4M7.523 7.769l.646 1.77h7.662l.646-1.77zm-.092 2.77l-.97-2.77H4V4h16v3.77h-2.461l-1.074 2.769z");
}

</style>
