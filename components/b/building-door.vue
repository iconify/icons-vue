<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssa8p6a4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ssa8p6a4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:building-door" /></template>
