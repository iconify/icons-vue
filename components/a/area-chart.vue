<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkxa0gb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dkxa0gb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:area-chart" /></template>
