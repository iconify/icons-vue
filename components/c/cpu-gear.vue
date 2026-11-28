<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmpinr99k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmpinr99k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cpu-gear" /></template>
