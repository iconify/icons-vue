<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-ffzyhaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:clock-loader-20-sharp" /></template>
<style>
.w-ffzyhaw {
  fill: currentColor;
  d: path("M8.1 21.213q-1.825-.788-3.175-2.138T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22t-3.9-.788m9.575-3.537Q20 15.35 20 12h-8V4Q8.65 4 6.325 6.325T4 12t2.325 5.675T12 20t5.675-2.325");
}

</style>
