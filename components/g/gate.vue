<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6tyn2y3f.css';
import '../../css/c/cel95e31f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="f6tyn2y3f"/><path class="cel95e31f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:gate" /></template>
