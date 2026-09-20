<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg8x53b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg8x53b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:collapse-vertical-line" /></template>
