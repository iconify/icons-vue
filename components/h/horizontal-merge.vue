<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqga2hl6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqga2hl6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:horizontal-merge" /></template>
