<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="g9zn-0bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:autocorrect-28-regular" /></template>
<style>
.g9zn-0bdn {
  fill: currentColor;
  d: path("M11.687 6.247c1.091-1.665 3.535-1.655 4.612.019L19.99 12h5.261a.75.75 0 0 1 0 1.5h-4.296l.506.786A5.47 5.47 0 0 1 22.5 17.5A5.5 5.5 0 1 1 17 12h1.205l-3.167-4.923a1.25 1.25 0 0 0-2.096-.008L3.377 21.661a.75.75 0 0 1-1.254-.821zM17 13.5a4 4 0 1 0 0 8a4 4 0 0 0 0-8");
}

</style>
