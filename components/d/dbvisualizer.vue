<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-k0yub0q.css';
import '../../css/t/tyr-cab1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="r-k0yub0q"/><path class="tyr-cab1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:dbvisualizer" /></template>
