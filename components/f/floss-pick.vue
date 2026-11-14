<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bud21abhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:floss-pick" /></template>
<style>
.bud21abhh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m15.358 2.985l5.657 5.657q.106.105.163.243t.057.287t-.057.287t-.163.243l-3.535 3.535q-.172.173-.413.211l-5.524.872q.622 1.403-.781 2.806L7.58 20.308q-1.944 1.944-3.888 0t0-3.888l3.182-3.182q1.403-1.403 2.806-.781l.872-5.524q.038-.241.211-.413l3.535-3.535q.105-.106.243-.163t.287-.057t.287.057t.243.163m4.066 6.187l-4.596-4.596l-2.832 2.832l-.862 5.458l5.458-.862z");
}

</style>
