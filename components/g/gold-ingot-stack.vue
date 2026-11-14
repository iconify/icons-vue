<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvh5ums7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gold-ingot-stack" /></template>
<style>
.xvh5ums7o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.238 9.954q-.172.69.05 1.296H4.921q-1.756 0-2.183 1.704l-.5 2q-.266 1.065.41 1.93q.675.866 1.773.866h4.158q1.098 0 1.773-.866q.676-.865.41-1.93l-.5-2q-.027-.105-.058-.204h3.592q-.031.099-.058.204l-.5 2q-.266 1.065.41 1.93q.675.866 1.773.866h4.158q1.098 0 1.773-.866q.676-.865.41-1.93l-.5-2q-.427-1.704-2.183-1.704h-2.367q.222-.606.05-1.296l-.5-2q-.427-1.704-2.183-1.704H9.921q-1.756 0-2.183 1.704z");
}

</style>
