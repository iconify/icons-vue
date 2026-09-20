<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h-q1h1b6z"/><path class="egjbh5z1v"/><path class="y9z4e7b5s"/><path class="v12a-k2cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-banknote-with-dollar-sign" /></template>
<style>
.egjbh5z1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.297 13.005v21.99c0 .079-.015.15-.037.223a.75.75 0 0 1-.712.496H18.05a.75.75 0 0 1-.712-.496a.7.7 0 0 1-.037-.223v-21.99c0-.079.015-.15.037-.223a.75.75 0 0 1 .712-.496h11.497a.75.75 0 0 1 .712.496a.7.7 0 0 1 .037.223");
}

.h-q1h1b6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.297 14.411h6.635c.097 1.584 1.431 2.823 3.035 2.823c.112 0 .225 0 .322-.007v13.448c-.097-.008-.21-.008-.322-.008c-1.611 0-2.96 1.262-3.035 2.861h-6.635m-12.995 0h-6.263c-.068-1.6-1.41-2.86-3.036-2.86q-.157-.002-.292.007V17.227q.135.009.292.007c1.62 0 2.953-1.239 3.035-2.823h6.264");
}

.v12a-k2cy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.297 17.678c3.991.024 5.609 3.983 5.609 6.063c0 2.098-1.868 6.128-5.609 6.084m-12.995 0c-4.428 0-5.635-4.3-5.635-6.084c0-1.93 1.01-6.063 5.635-6.063m4.956 9.419c.441.575.995.79 1.765.79h1.066c.992 0 1.796-.807 1.796-1.8c0-.995-.804-1.8-1.796-1.8H23.91a1.8 1.8 0 0 1-1.796-1.8c0-.995.804-1.8 1.796-1.8h1.066c.77 0 1.324.213 1.765.788m-2.241-.789v-.9m0 9v-.9");
}

.y9z4e7b5s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.04 35.714H6.25a.75.75 0 0 1-.75-.751V13.037a.75.75 0 0 1 .75-.75h11.8m11.498-.001H41.75a.75.75 0 0 1 .749.751v21.926a.75.75 0 0 1-.75.75H29.56");
}

</style>
