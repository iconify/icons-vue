<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tv54ryb9l"/><path class="lrz9o2brp"/><path class="m9-1yib4s"/><path class="wamcsshpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:locked-with-pen" /></template>
<style>
.lrz9o2brp {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M28 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V18a4 4 0 0 1 4-4h20a4 4 0 0 1 4 4z");
}

.m9-1yib4s {
  fill: var(--svg-color--66757f, #66757f);
  d: path("m32 21l-16-4l-11 7h12.184A2.99 2.99 0 0 1 20 22a3 3 0 0 1 0 6a2.99 2.99 0 0 1-2.816-2H5l11 7l16-4l-1-4z");
}

.tv54ryb9l {
  fill: var(--svg-color--aab8c2, #aab8c2);
  d: path("M14 0C8.477 0 4 4.477 4 10v10h4V10a6 6 0 0 1 6-5.999A6 6 0 0 1 20 10v10h4V10c0-5.523-4.477-10-10-10");
}

.wamcsshpm {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M36 17h-3c-.55 0-1.201.402-1.447.894l-3.105 6.211c-.246.492-.246 1.297 0 1.789l3.105 6.211c.246.493.897.895 1.447.895h3z");
}

</style>
