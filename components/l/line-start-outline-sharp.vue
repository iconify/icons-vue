<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx_y7kbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-start-outline-sharp" /></template>
<style>
.yx_y7kbnk {
  fill: currentColor;
  d: path("M4.5 14.5q-1.05 0-1.775-.725T2 12t.725-1.775T4.5 9.5q.775 0 1.4.425T6.8 11H22v2H6.8q-.275.65-.9 1.075t-1.4.425");
}

</style>
