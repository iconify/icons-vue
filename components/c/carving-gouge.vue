<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfyoetuyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:carving-gouge" /></template>
<style>
.nfyoetuyt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.006 8.296q-2.366 2.286-4.696.455l-1.87 1.87q1.519 2.015-.496 4.03l-4.242 4.243q-.952.952-2.298.952t-2.298-.952t-.952-2.298t.952-2.298l4.243-4.242q2.015-2.015 4.03-.496l1.87-1.87q-1.831-2.33.455-4.696q.051-.053.112-.095q.06-.042.128-.072t.14-.045q.072-.016.146-.017t.147.012t.141.04t.131.067t.115.092q.107.103.167.24q.059.137.062.286q.002.149-.052.288q-.055.139-.159.246q-1.536 1.591.028 3.154q1.563 1.564 3.154.028q.053-.052.115-.092t.131-.067t.141-.04q.073-.013.147-.012t.146.017t.14.045q.068.03.128.072q.061.042.112.095q.104.107.159.246q.054.139.052.288t-.062.286t-.167.24");
}

</style>
