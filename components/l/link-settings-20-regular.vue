<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o3m0-mchr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:link-settings-20-regular" /></template>
<style>
.o3m0-mchr {
  fill: currentColor;
  d: path("M12.06 8.901a2 2 0 0 0 2.9.001l.493-.518a5.3 5.3 0 0 1 1.485.922l-.187.63a2 2 0 0 0 1.45 2.511l.54.13a5.7 5.7 0 0 1 .005 1.807l-.584.144a2 2 0 0 0-1.44 2.496l.197.687c-.44.382-.94.692-1.482.912l-.5-.524a2 2 0 0 0-2.898 0l-.493.518a5.3 5.3 0 0 1-1.484-.922l.186-.63a2 2 0 0 0-1.45-2.511l-.54-.13a5.7 5.7 0 0 1-.006-1.808l.584-.144a2 2 0 0 0 1.441-2.496l-.198-.686a5.3 5.3 0 0 1 1.483-.913zM13.5 12c-.8 0-1.449.672-1.45 1.5S12.7 15 13.5 15s1.45-.672 1.45-1.5S14.3 12 13.5 12M8 4a.5.5 0 0 1 .09.992L8 5H6a3 3 0 0 0-.197 5.993L6 11h1.499a6.5 6.5 0 0 0-.323 1H6a4 4 0 0 1-.22-7.994L6 4zm6 0a4 4 0 0 1 3.93 4.745a6.5 6.5 0 0 0-.931-.722L17 8a3 3 0 0 0-2.803-2.993L14 5h-2a.5.5 0 0 1-.09-.992L12 4zm-3.003 3.5a6.5 6.5 0 0 0-1.65 1H6a.5.5 0 0 1-.09-.992L6 7.5z");
}

</style>
