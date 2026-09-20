<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j29l6eqzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j29l6eqzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:life-ring" /></template>
