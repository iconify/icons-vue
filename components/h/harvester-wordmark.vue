<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is3doibbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="is3doibbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:harvester-wordmark" /></template>
