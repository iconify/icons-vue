<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rltfo1biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rltfo1biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrows-from-axis-horizontal" /></template>
