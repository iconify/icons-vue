<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7vpm1bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7vpm1bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-bar-gloss" /></template>
