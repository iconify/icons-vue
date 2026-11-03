<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o-olbub-i"/><path clip-rule="evenodd" class="pxg_586wu"/><path clip-rule="evenodd" class="ck1iowbek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bus-front-duotone" /></template>
<style>
.ck1iowbek {
  fill-rule: evenodd;
  d: path("M9 14C9 14.5523 8.5523 15 8 15C7.4477 15 7 14.5523 7 14C7 13.4477 7.4477 13 8 13C8.5523 13 9 13.4477 9 14ZM17 14C17 14.5523 16.5523 15 16 15C15.4477 15 15 14.5523 15 14C15 13.4477 15.4477 13 16 13C16.5523 13 17 13.4477 17 14Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.o-olbub-i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 7.0001C3 4.2386 5.2386 2 8 2L16 2C18.7614 2 21 4.2386 21 7.0001L22 7.0001C22.5523 7.0001 23 7.4478 23 8.0001C23 8.5524 22.5523 9.0001 22 9.0001L21 9.0001L21 10.0001C21 10.0027 21 10.0053 21 10.0079L21 18C21 18.5523 20.5523 19 20 19L4 19C3.4477 19 3 18.5523 3 18L3 9.0001L2 9.0001C1.4477 9.0001 1 8.5524 1 8.0001C1 7.4478 1.4477 7.0001 2 7.0001L3 7.0001Z");
}

.pxg_586wu {
  fill-rule: evenodd;
  d: path("M13 4L16 4C17.6568 4 19 5.3432 19 7L19 9L13 9L13 4ZM11 9L5 9L5 7C5 5.3432 6.3432 4 8 4L11 4L11 9ZM16 17L20 17C20.5523 17 21 17.4477 21 18L21 19.5C21 20.8807 19.8807 22 18.5 22L17.5 22C16.1193 22 15 20.8807 15 19.5L15 18C15 17.4477 15.4477 17 16 17ZM4 17L8 17C8.5523 17 9 17.4477 9 18L9 19.5C9 20.8807 7.8807 22 6.5 22L5.5 22C4.1193 22 3 20.8807 3 19.5L3 18C3 17.4477 3.4477 17 4 17Z");
}

</style>
