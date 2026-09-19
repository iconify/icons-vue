<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nydjrrbmo"/><path class="f9fs8xtpc"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kvaesitso" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f9fs8xtpc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.926 19.778v7.807c0 .958.777 1.734 1.735 1.734h24.287c.958 0 1.734-.776 1.734-1.734v-7.807c0-.958-.776-1.735-1.735-1.735H11.661c-.958 0-1.735.777-1.735 1.735m25.572 22.388v-7.863a2 2 0 0 0-2-2H14.11a2 2 0 0 0-2 2v7.61");
}

.nydjrrbmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.983 20.862h5.638V26.5h-5.638zm-7.936 0h5.638V26.5h-5.638zm-7.937 0h5.638V26.5H13.11zm-4.474-5.103l13.46-6.715a4.15 4.15 0 0 1 3.66-.023L39.365 15.6");
}

</style>
