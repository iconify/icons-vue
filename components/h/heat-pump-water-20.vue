<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnl7id0ua.css';
import '../../css/k/k4v56fbhg.css';
import '../../css/c/ci9x7ub2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vnl7id0ua"/><path class="k4v56fbhg"/><path class="ci9x7ub2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-pump-water-20" /></template>
