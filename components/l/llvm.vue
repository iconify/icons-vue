<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4y3p3btl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="j4y3p3btl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:llvm" /></template>
