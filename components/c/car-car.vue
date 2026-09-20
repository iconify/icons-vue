<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl8f78rzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rl8f78rzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:car-car" /></template>
