<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjw_-c3ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:adaptive-spoon" /></template>
<style>
.tjw_-c3ji {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 7q0-2.091 1.005-3.598Q14.856 1.75 16.5 1.75t2.745 1.652Q20.25 4.909 20.25 7t-1.005 3.598Q18.144 12.25 16.5 12.25q-1.576 0-2.653-1.517l-1.505 3.01q.499.73.499 1.666q0 1.243-.879 2.121L8.78 20.712q-.878.879-2.121.879t-2.121-.879q-.879-.878-.879-2.121t.879-2.121l3.182-3.182q.878-.879 2.121-.879q.732 0 1.338.305l1.4-2.799q.043-.087.107-.159q.063-.073.143-.127T13 9.543t.186-.04Q12.75 8.378 12.75 7");
}

</style>
