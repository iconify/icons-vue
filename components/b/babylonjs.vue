<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfcnzlb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rfcnzlb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:babylonjs" /></template>
