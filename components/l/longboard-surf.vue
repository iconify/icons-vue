<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpe6rbb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:longboard-surf" /></template>
<style>
.gpe6rbb4e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.907 8.907Q3.25 14.564 3.25 19q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q1.739 0 3.665-.869l2.878 2.213q.058.046.124.078q.067.033.138.052t.145.024t.147-.004t.143-.034q.07-.023.134-.06t.12-.086t.1-.107q.057-.073.093-.157q.037-.085.053-.175q.015-.091.008-.183t-.036-.179l-1.057-3.171q1.658-1.22 3.438-2.999Q19.75 8.436 19.75 4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 3.25q-4.436 0-10.093 5.657m.458 9.06l.148.443l-.387-.297z");
}

</style>
