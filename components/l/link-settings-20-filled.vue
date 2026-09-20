<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k1s4peiwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:link-settings-20-filled" /></template>
<style>
.k1s4peiwk {
  fill: currentColor;
  d: path("M12.06 8.901a2 2 0 0 0 2.9.001l.493-.518a5.3 5.3 0 0 1 1.485.922l-.187.63a2 2 0 0 0 1.45 2.511l.54.13a5.7 5.7 0 0 1 .005 1.807l-.584.144a2 2 0 0 0-1.44 2.496l.197.687c-.44.382-.94.692-1.482.912l-.5-.524a2 2 0 0 0-2.898 0l-.493.518a5.3 5.3 0 0 1-1.484-.922l.186-.63a2 2 0 0 0-1.45-2.511l-.54-.13a5.7 5.7 0 0 1-.006-1.808l.584-.144a2 2 0 0 0 1.441-2.496l-.198-.686a5.3 5.3 0 0 1 1.483-.913zM13.5 12c-.8 0-1.449.672-1.45 1.5S12.7 15 13.5 15s1.45-.672 1.45-1.5S14.3 12 13.5 12M8 4a.75.75 0 0 1 .75.75c0 .43-.344.723-.75.75H6a2.5 2.5 0 0 0-.164 4.995L6 10.5h1.733c-.244.47-.433.972-.557 1.5H6a4 4 0 0 1-.2-7.995L6 4zm3.717 3.25a6.5 6.5 0 0 0-2.652 1.5H6.25a.75.75 0 0 1-.102-1.493l.102-.007zM14 4a4 4 0 0 1 3.93 4.745a6.5 6.5 0 0 0-1.447-1.02a2.5 2.5 0 0 0-2.319-2.22L14 5.5h-2a.75.75 0 0 1-.102-1.493L12 4z");
}

</style>
