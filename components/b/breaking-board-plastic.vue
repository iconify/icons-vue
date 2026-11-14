<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqn20wjdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:breaking-board-plastic" /></template>
<style>
.yqn20wjdi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.797 4.25h1.953q1.036 0 1.768.732t.732 1.768v8q0 1.036-.732 1.768t-1.768.732h-4.388q-1.259 0-2.009-1.012q-.749-1.012-.382-2.217l2.433-7.999q.54-1.773 2.393-1.772m-7.659 2.5H4.25q-2.5 0-2.5 2.5v8q0 2.5 2.5 2.5h3.453q1.852.001 2.393-1.772l2.433-7.999q.367-1.205-.382-2.217q-.75-1.012-2.009-1.012");
}

</style>
