<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah81sc2kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ah81sc2kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:link" /></template>
