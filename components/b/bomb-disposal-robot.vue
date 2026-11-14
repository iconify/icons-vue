<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fth4_4fhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bomb-disposal-robot" /></template>
<style>
.fth4_4fhm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.414 4.031L10.64 8.75H6.25q-2.5 0-2.5 2.5v2.5q0 .649.288 1.18q-2.288.641-2.288 3.57q0 3.75 3.75 3.75h9q3.75 0 3.75-3.75t-3.75-3.75h-.45q.2-.459.2-1v-2.5q0-2.088-1.744-2.432l2.52-3.15l2.531 2.894l-1.681 2.522q-.041.061-.069.13q-.028.068-.043.14t-.014.147t.015.146q.014.073.042.141t.07.129t.093.114q.053.052.114.093t.13.069t.14.043q.073.014.147.014t.146-.015q.073-.014.141-.042t.129-.07t.114-.093q.052-.053.093-.114l1.633-2.449l2.408 1.204q.066.033.137.052q.071.02.145.025t.147-.004t.143-.032t.134-.06t.12-.085t.101-.107t.079-.125q.067-.133.077-.282q.011-.149-.036-.29q-.048-.142-.145-.254q-.098-.113-.232-.18l-2.868-1.434l-3.403-3.889q-.043-.05-.095-.092q-.117-.093-.26-.134t-.292-.025q-.148.016-.279.088q-.13.072-.224.188");
}

</style>
