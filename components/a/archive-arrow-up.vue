<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9ifqu2ej.css';
import '../../css/i/iqx54slxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9ifqu2ej"/><path class="iqx54slxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:archive-arrow-up" /></template>
