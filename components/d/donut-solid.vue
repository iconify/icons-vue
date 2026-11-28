<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekz35oeaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekz35oeaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:donut-solid" /></template>
