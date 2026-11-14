<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f46no9bxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:champions" /></template>
<style>
.f46no9bxa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.25 9.5l.852.947a1.5 1.5 0 0 0 2.422-.268l2.169-3.855a1.5 1.5 0 0 1 2.614 0l2.169 3.855a1.5 1.5 0 0 0 2.422.268l.852-.947a.923.923 0 0 1 1.59.798l-1.099 5.496A1.5 1.5 0 0 1 17.77 17H6.23a1.5 1.5 0 0 1-1.471-1.206L3.66 10.298A.923.923 0 0 1 5.25 9.5M5 20.5h14M12 13h.01");
}

</style>
