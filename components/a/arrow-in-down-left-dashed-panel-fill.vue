<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9fvg1b0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9fvg1b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-in-down-left-dashed-panel-fill" /></template>
