<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osl8gwbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osl8gwbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:drag-horizontal-round" /></template>
