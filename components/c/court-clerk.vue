<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z5s4qzbwl"/><path class="b3ghh5bgo"/><path class="uj2oiop0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:court-clerk" /></template>
<style>
.b3ghh5bgo {
  d: path("M14.75 16.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

.uj2oiop0t {
  d: path("M15.75 18.75v3l1.75-1l1.75 1v-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z5s4qzbwl {
  d: path("M21 12.422V2.5c-3-.25-7 .25-9 1.5c-2-1.25-6-1.75-9-1.5V15c2.995-.25 6.986.248 8.99 1.494M12 4v12.5");
}

</style>
