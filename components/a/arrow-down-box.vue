<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk10_ekef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="mk10_ekef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-down-box" /></template>
