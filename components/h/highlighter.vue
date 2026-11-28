<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez5rt2sqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ez5rt2sqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:highlighter" /></template>
