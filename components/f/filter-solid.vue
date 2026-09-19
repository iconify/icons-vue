<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cys704nul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cys704nul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:filter-solid" /></template>
