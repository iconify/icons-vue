<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rudv-ybyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fire-class-abc" /></template>
<style>
.rudv-ybyv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.5 1.75h-5q-3.21 0-5.48 2.27T1.75 9.5v5q0 3.21 2.27 5.48t5.48 2.27h5q3.21 0 5.48-2.27t2.27-5.48v-5q0-3.21-2.27-5.48T14.5 1.75m-1.97 4.22q4.72 4.719 4.72 8.03q0 2.175-1.538 3.712Q14.175 19.25 12 19.25t-3.712-1.538Q6.75 16.175 6.75 14q0-3.06 2.531-5.086q.058-.046.124-.08q.065-.034.136-.054q.071-.021.145-.027q.073-.007.147.002q.073.008.144.03t.135.058t.121.083t.103.105q.122.153.154.346q.072.432.188.78q-.163-2.365.651-3.992q.033-.066.079-.125q.045-.058.101-.107q.055-.048.12-.085q.064-.036.134-.06q.07-.023.143-.032t.147-.004t.145.025t.137.052q.109.055.195.141");
}

</style>
