<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="o6wyygb4v"/><path class="r87seac0a"/><ellipse class="kairyqb8r"/><path class="bjhus3beg"/><path class="cnv1bngns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-in-hole" /></template>
<style>
.bjhus3beg {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M10 4v26c0 .553.448.844 1 .844s1-.291 1-.844V4z");
}

.cnv1bngns {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M10 3C10 .8 11.695-.395 13.767.345l9.466 3.381c2.071.74 2.071 1.951 0 2.69l-9.466 3.381C11.695 10.538 10 9.343 10 7.143z");
}

.kairyqb8r {
  cx: 12.5px;
  cy: 30.5px;
  fill: var(--svg-color--292f33, #292f33);
  rx: 6.5px;
  ry: 2.5px;
}

.o6wyygb4v {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M4 36h28c2 0 3.731-2 3.731-4c0-4.355-4.634-11-17.731-11C4.508 21 .193 27.459.193 32C.193 34 2 36 4 36");
}

.r87seac0a {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M11.292 29.5s.958.667 1.958.667c2.208-4.875 13-7.5 14-7.5c.15 0 .33-.018.512-.047a21 21 0 0 0-2.33-.737c-4.626.063-13.031 3.917-14.14 7.617");
}

</style>
