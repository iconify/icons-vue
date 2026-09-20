<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="v1ej-6mrm"/><path class="stritzb2o"/></g><g class="to-5kdesz"><path class="wfpy3gbmy"/><path class="abq6bsu5h"/><path class="rtndkv_2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-kash-30" /></template>
<style>
.abq6bsu5h {
  stroke-linecap: round;
  d: path("M39.9 16.105v23.412a4 4 0 0 1-4 4h-25a4 4 0 0 1-4-4v-25a4 4 0 0 1 4-4h14.953m-12.961-3l.016 6");
}

.rtndkv_2k {
  d: path("M39.9 16.105a3.985 3.985 0 1 0 0-7.97c-.086 0-.167.02-.253.025c-.653-2.123-2.608-3.677-4.946-3.677S30.41 6.036 29.755 8.16c-.085-.005-.166-.025-.252-.025a3.985 3.985 0 0 0 0 7.97z");
}

.stritzb2o {
  d: path("M14.942 26.97c.775-.646 1.61-.94 3.485-.936l.436.003a2.8 2.8 0 0 1 0 5.599m-2.152-.001h2.152");
}

.to-5kdesz {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

.v1ej-6mrm {
  d: path("M24.428 33.411c0 2.074 1.66 3.733 3.733 3.733s3.595-1.659 3.595-3.733v-3.733c0-2.074-1.659-3.734-3.595-3.734s-3.733 1.66-3.733 3.734zm-9.485 2.879c.773.647 1.608.944 3.483.944h.437a2.8 2.8 0 0 0 0-5.599");
}

.wfpy3gbmy {
  stroke-linecap: round;
  d: path("M39.9 19.661h-33m33-3.556v23.412a4 4 0 0 1-4 4h-25a4 4 0 0 1-4-4v-25a4 4 0 0 1 4-4h14.953");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
