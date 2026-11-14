<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2_j46b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:explore-grid" /></template>
<style>
.l2_j46b8i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m14.16-1.394q.657-1.217-.321-2.195t-2.195-.321L10.54 9.627q-.129.069-.244.151q-.188.054-.326.192t-.192.326q-.082.116-.151.244L8.09 13.394q-.657 1.217.321 2.195t2.195.321l2.854-1.537q.129-.069.244-.151q.188-.054.326-.192t.192-.326q.082-.116.151-.244z");
}

</style>
