<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_1rdccum.css';
import '../../css/m/mptrtbrij.css';
import '../../css/q/qi6_u5bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t_1rdccum"/><path class="mptrtbrij"/><path class="qi6_u5bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flywheel-20-bold" /></template>
