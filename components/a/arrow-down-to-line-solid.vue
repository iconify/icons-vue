<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dahe0tbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dahe0tbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-down-to-line-solid" /></template>
