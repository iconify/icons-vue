<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyj2c0vnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyj2c0vnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:filter-x" /></template>
