<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxm7rxoyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flame-map-pin-corner-fill" /></template>
<style>
.oxm7rxoyc {
  fill: currentColor;
  d: path("M14.205 10.689A6.01 6.01 0 0 0 11 16v4.917a1 1 0 0 1-.835.986A7 7 0 0 1 9 22a6.9 6.9 0 0 1-2.725-.551A6.99 6.99 0 0 1 2 15c0-1.301.344-2.756 1.291-3.705l.002-.002A1 1 0 0 1 5 12a.999.999 0 1 0 2 0c0-.365-.035-.737-.152-1.085c-.1-.298-.26-.579-.413-.853a17 17 0 0 1-.329-.615c-1.451-2.903-.063-5.361 2.269-7.228a1 1 0 0 1 1.606.585a8 8 0 0 0 1.281 3.004c.635.925 1.442 1.72 2.338 2.392a1 1 0 0 1 .107.093q.447.447.809.964a1 1 0 0 1-.311 1.432m2.24 11.143C14.588 20.594 13 18.286 13 16a4 4 0 0 1 .315-1.557c.2-.476.491-.907.857-1.271A3.98 3.98 0 0 1 17 12c1.064 0 2.078.418 2.828 1.172c.366.364.657.795.857 1.271c.209.492.316 1.022.315 1.557c0 2.286-1.588 4.594-3.445 5.832a1 1 0 0 1-1.11 0M17 17h.01a1 1 0 0 0 0-2H17a1 1 0 0 0-.925.621a.99.99 0 0 0 .216 1.085l.002.001l.001.001A1 1 0 0 0 17 17");
}

</style>
