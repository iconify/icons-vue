<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p836djbgm"/><path class="rqvjp3byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hue-essentials" /></template>
<style>
.p836djbgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4c5.86 0 12.46.98 12.46 4.95c0 4.898-6.806 17.839-6.806 26.913c0 1.598-1.031 1.753-2.165 1.753H20.51c-1.135 0-2.165-.155-2.165-1.753c0-9.074-6.806-22.015-6.806-26.913C11.54 4.98 18.14 4 24 4");
}

.rqvjp3byy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.714 16.033c-.822 2.39-6.985 2.145-10.714 2.145s-9.891.246-10.714-2.145m14.411 21.578v2.694a1.84 1.84 0 0 1-1.839 1.839h-.02v.017a1.839 1.839 0 1 1-3.678 0v-.017h-.018a1.84 1.84 0 0 1-1.84-1.839v-2.694");
}

</style>
