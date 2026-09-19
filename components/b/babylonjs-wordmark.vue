<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4g0wfbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="g4g0wfbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:babylonjs-wordmark" /></template>
