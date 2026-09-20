<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwpx3jb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:genres-outline-rounded" /></template>
<style>
.iwpx3jb9s {
  fill: currentColor;
  d: path("M12.125 17.125Q13 16.25 13 15V8h2q.425 0 .713-.288T16 7t-.288-.712T15 6h-2.5q-.425 0-.712.288T11.5 7v5.4q-.35-.2-.725-.3T10 12q-1.25 0-2.125.875T7 15t.875 2.125T10 18t2.125-.875M12 22q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22m0-2q3.35 0 5.675-2.325T20 12t-2.325-5.675T12 4T6.325 6.325T4 12t2.325 5.675T12 20m0-8");
}

</style>
