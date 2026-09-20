<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="o205f_btu"/><path class="vlfltdbow"/><g class="y_9pn2b8h"><path class="v3ecz8oux"/><circle class="zueid1b7j"/><circle class="a6ecueb_o"/></g><path class="g_2zs9bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:cinema" /></template>
<style>
.a6ecueb_o {
  cx: 90.451px;
  cy: 44.35px;
  r: 14.4px;
}

.g_2zs9bjv {
  fill: var(--svg-color--b4e1ed, #b4e1ed);
  d: path("M39.7 12.9c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.o205f_btu {
  fill: var(--svg-color--427687, #427687);
  d: path("M116 4H12c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8V12c0-4.42-3.58-8-8-8");
}

.v3ecz8oux {
  d: path("M95.65 57.95h-47.2a5.763 5.763 0 0 0-5.7 5.7v9.4l-21-14.7a3.798 3.798 0 0 0-5.5 3.4v37.7a3.84 3.84 0 0 0 3.9 3.78c.55-.01 1.1-.14 1.6-.38l21-14.7v9.4c0 3.15 2.55 5.7 5.7 5.7h47.2a5.763 5.763 0 0 0 5.7-5.7v-34c-.04-3.11-2.59-5.61-5.7-5.6");
}

.vlfltdbow {
  fill: var(--svg-color--8cafbf, #8cafbf);
  d: path("M109.7 4H11.5A7.555 7.555 0 0 0 4 11.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.5c.09-4.05-3.13-7.41-7.18-7.5z");
}

.y_9pn2b8h {
  fill: var(--svg-color--fafafa, #fafafa);
}

.zueid1b7j {
  cx: 55.351px;
  cy: 38.15px;
  r: 20.5px;
}

</style>
