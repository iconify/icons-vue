<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odp-njbud.css';
import '../../css/r/rxyy9rljh.css';
import '../../css/q/q5dzxvb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="odp-njbud"/><path class="rxyy9rljh"/><path class="q5dzxvb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-left-bold" /></template>
