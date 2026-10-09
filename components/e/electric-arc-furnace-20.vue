<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/occ8gwb-f.css';
import '../../css/j/jl4qfih3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="occ8gwb-f"/><path class="jl4qfih3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-arc-furnace-20" /></template>
