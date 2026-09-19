<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lovg5vbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lovg5vbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:bevyengine" /></template>
