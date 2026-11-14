<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysxqymgqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:give-way" /></template>
<style>
.ysxqymgqm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.96 3.25H7.04q-1.947 0-2.922 1.686t-.003 3.373l4.96 8.614q.974 1.691 2.925 1.691t2.925-1.691l4.96-8.614q.972-1.687-.003-3.373T16.96 3.25m-6.636 3h3.352q1.293 0 1.944 1.117q.651 1.118.013 2.243l-1.676 2.957q-.646 1.14-1.957 1.14t-1.957-1.14L8.367 9.61q-.638-1.125.013-2.243t1.944-1.117");
}

</style>
