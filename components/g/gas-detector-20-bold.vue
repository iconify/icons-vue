<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfzjs4b6t.css';
import '../../css/y/y4dvfdc8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nfzjs4b6t"/><path class="y4dvfdc8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-detector-20-bold" /></template>
