<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gro8lebrz.css';
import '../../css/w/w05qs9b8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gro8lebrz"/><path class="w05qs9b8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:loft-insulation-20-bold" /></template>
