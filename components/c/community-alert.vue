<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b3s77qbxi"/><path class="a_uz0srsp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:community-alert" /></template>
<style>
.a_uz0srsp {
  d: path("M12.621 18.383q-.123-.047-.238-.113q-.114-.065-.218-.147q-.103-.081-.193-.178t-.165-.205t-.132-.227t-.096-.245t-.059-.256t-.02-.262V9.225q0-.172.034-.342q.033-.169.099-.328t.162-.303t.218-.265l2.75-2.75q.061-.061.127-.115q.067-.055.138-.102q.072-.048.147-.089q.076-.04.156-.073q.079-.033.161-.058t.167-.042q.084-.016.17-.025q.085-.008.171-.008t.171.008q.086.009.17.025q.085.017.167.042t.161.058t.156.073q.075.041.147.089q.071.047.138.102q.066.054.127.115l2.75 2.75q.122.122.218.265t.162.303t.099.328q.034.17.034.342v4.304m-1.158 2.904l1.323 2.646a1.5 1.5 0 0 1-1.342 2.171h-2.646a1.5 1.5 0 0 1-1.342-2.171l1.323-2.646a1.5 1.5 0 0 1 2.684 0M18 17.25V19");
}

.b3s77qbxi {
  d: path("m3.013 9.987l2.75-2.75a1.75 1.75 0 0 1 2.474 0l2.75 2.75a1.75 1.75 0 0 1 .513 1.238v5.525a1.75 1.75 0 0 1-1.75 1.75h-5.5a1.75 1.75 0 0 1-1.75-1.75v-5.525a1.75 1.75 0 0 1 .513-1.238");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
