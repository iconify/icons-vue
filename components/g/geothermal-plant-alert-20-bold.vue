<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d25p8sb0p.css';
import '../../css/j/j1ynsb0aw.css';
import '../../css/z/z0v5_fbef.css';
import '../../css/j/jeyqzjnhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d25p8sb0p"/><path class="j1ynsb0aw"/><path class="z0v5_fbef"/><path class="jeyqzjnhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:geothermal-plant-alert-20-bold" /></template>
