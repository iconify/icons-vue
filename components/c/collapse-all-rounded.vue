<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p81kqjbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:collapse-all-rounded" /></template>
<style>
.p81kqjbhy {
  fill: currentColor;
  d: path("m12 17.4l-3.9 3.9q-.275.275-.7.275t-.7-.275t-.275-.7t.275-.7l3.875-3.875q.575-.575 1.425-.575t1.425.575L17.3 19.9q.275.275.275.7t-.275.7t-.7.275t-.7-.275zm0-10.8l3.9-3.9q.275-.275.7-.275t.7.275t.275.7t-.275.7l-3.875 3.875Q12.85 8.55 12 8.55t-1.425-.575L6.7 4.1q-.275-.275-.275-.7t.275-.7t.7-.275t.7.275z");
}

</style>
