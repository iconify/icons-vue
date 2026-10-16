<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afx4zacet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="afx4zacet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:infrared-panel-20-bold" /></template>
