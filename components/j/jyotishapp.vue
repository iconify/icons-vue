<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cwbwgz49y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jyotishapp" /></template>
<style>
.cwbwgz49y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.972 34.49c.092.24 5.352 7.52 12.116 3.986c9.292-4.855 1.651-16.629-.728-20.257c-2.324-3.543-3.76-11.394 2.275-13.626c-2.989 3.46-1.189 6.305-.176 7.893c1.967 3.084 5.866 6.457 9.37 12.357c3.232 5.865 1.633 13.385-3.656 16.489c-5.59 3.28-12.579 2.76-16.745-2.205s-3.846-12.29.737-16.874c0 4.585 3.53 5.786 5.16 5.289c1.631-.498 5.432-1.323 3.035-9.324");
}

</style>
