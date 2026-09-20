<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5k2-3dhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="t5k2-3dhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-down-bold" /></template>
