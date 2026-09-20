<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="s_vcnzb6j"/><path class="jdn_4sb3z"/><path class="n50j76buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:krungsri-wealth-will" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.jdn_4sb3z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.228 27.991l-2.93-1.62c-.852-.473-1.457-1.522-1.179-2.357c.233-.698 1.257-1.126 1.96-.952c.793.195 1.517 1.135 1.478 1.981c-.148 3.269-3.562 7.451-5.557 8.203c-1.995-.752-5.409-4.934-5.557-8.203c-.039-.846.685-1.786 1.477-1.981c.704-.174 1.728.254 1.96.952c.28.835-.326 1.884-1.179 2.356l-2.93 1.621");
}

.n50j76buw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.24 30.959c1.801-1.795 2.94-3.648 1.546-4.25h2.428c-1.395.602-.255 2.455 1.545 4.25");
}

.s_vcnzb6j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.246 27.672a9.246 9.246 0 0 1-18.492 0a9.246 9.246 0 0 1 18.492 0M32.127 5.52A9.25 9.25 0 0 1 24 10.358a9.25 9.25 0 0 1-8.127-4.836m15.389 9.11H42.5m-21.762 0h6.524m-21.762 0h11.238m2.153-5.718l-.298 11.153M29.109 8.914l.298 11.153");
}

</style>
