<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsuj73ltw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-jewelry" /></template>
<style>
.fsuj73ltw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 3.25h4.236q1.146 0 1.82.927l2.923 4.019q.228.314.347.629q-.154-.075-.326-.075h-9.929l1.634-4.494q.051-.14.044-.289t-.069-.284t-.173-.236t-.251-.152Q11.132 3.25 11 3.25m-2.525 5.5H4q-.172 0-.326.075q.119-.315.348-.629l2.922-4.019q.674-.927 1.82-.927H11q-.115 0-.226.035q-.11.034-.204.101q-.095.066-.165.158q-.07.091-.11.2zm-.054 1.5H4q-.18 0-.341-.082q.113.318.334.636l6.161 8.855q.381.548.926.784zm4.233 10.288q.721-.202 1.193-.88l6.16-8.854q.221-.318.334-.636q-.161.082-.341.082H9.971z");
}

</style>
