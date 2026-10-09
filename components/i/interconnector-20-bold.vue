<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4-gwpb0q.css';
import '../../css/o/o3015xv_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z4-gwpb0q"/><path class="o3015xv_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:interconnector-20-bold" /></template>
