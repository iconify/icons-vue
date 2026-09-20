<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="apcrt6bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:bowl-chopsticks-16-regular" /></template>
<style>
.apcrt6bnb {
  fill: currentColor;
  d: path("M2.732 1.078a.5.5 0 0 1 .69.154L7.092 7h1.815L5.578 1.77a.5.5 0 0 1 .844-.537L10.092 7H14.5a.5.5 0 0 1 .5.5V8A7 7 0 1 1 1 8v-.5a.5.5 0 0 1 .5-.5h4.407L2.578 1.77a.5.5 0 0 1 .154-.69M2.342 10h11.317A6 6 0 0 0 14 8H2c0 .701.12 1.375.341 2m.46 1A6 6 0 0 0 8 14c2.22 0 4.16-1.207 5.197-3z");
}

</style>
