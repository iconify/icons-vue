<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nww922agz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-alert-outline" /></template>
<style>
.nww922agz {
  fill: currentColor;
  d: path("M20.48 16.02q-.21-.209-.21-.52t.21-.52q.209-.21.52-.21t.52.21q.21.209.21.52t-.21.52q-.209.21-.52.21t-.52-.21m.02-2.904V7.5h1v5.616zM18.506 17H4.384q-.993 0-1.689-.695T2 14.615v-5.23q0-.994.696-1.69T4.385 7h13.73v1H4.386q-.589 0-.987.398T3 9.385v5.23q0 .589.398.987t.986.398h13.77q.038.287.126.53t.226.47M3 16V8z");
}

</style>
