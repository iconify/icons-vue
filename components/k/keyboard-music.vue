<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6x2qsxjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6x2qsxjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:keyboard-music" /></template>
