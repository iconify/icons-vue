<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfqk80y7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="dfqk80y7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:line-dotted" /></template>
