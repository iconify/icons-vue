<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k9a6izs2b"/><path class="c5uk8ubrb"/><path class="g2wj9jbhp"/><circle class="c2aqwjbng"/><circle class="qbu9qud0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:airbuds" /></template>
<style>
.c2aqwjbng {
  cx: 13.01px;
  cy: 25.793px;
  r: 0.75px;
  fill: currentColor;
}

.c5uk8ubrb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 27.918c1.788 2.574 4.307 3.596 7.637 2.898M28.925 42.5l.393-.596a.5.5 0 0 0-.413-.775l-2.58-.022a.499.499 0 0 1-.173-.967l2.417-.906a.501.501 0 0 0 .122-.87l-2.076-1.534a.5.5 0 0 1 .43-.884l3.376.933l-1.056-3.338a.499.499 0 0 1 .868-.462l1.609 2.018a.498.498 0 0 0 .864-.153l.857-2.565a.477.477 0 0 1 .929.13l.12 2.702a.5.5 0 0 0 .281.426c.165.082.36.065.51-.042l2.1-1.5a.5.5 0 0 1 .707.683l-1.423 2.152a.499.499 0 0 0 .414.775l2.58.022a.501.501 0 0 1 .172.968l-2.417.906a.498.498 0 0 0-.122.87l.877.648");
}

.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.k9a6izs2b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.291 41.119a8.96 8.96 0 0 1-4.79 1.38h-4.577M15 14.5h18M5.5 21.6a7.01 7.01 0 0 1 7.341-.849a7.01 7.01 0 0 1 3.35 9.324a7.01 7.01 0 0 1-10.69 2.505");
}

.qbu9qud0k {
  cx: 8.856px;
  cy: 23.836px;
  r: 0.75px;
  fill: currentColor;
}

</style>
