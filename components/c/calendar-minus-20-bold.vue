<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5wmwdblu.css';
import '../../css/k/kvqjz7b_z.css';
import '../../css/h/hayl1lfmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r5wmwdblu"/><path class="kvqjz7b_z"/><path class="hayl1lfmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-minus-20-bold" /></template>
