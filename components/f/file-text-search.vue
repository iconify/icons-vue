<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8m26mgwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8m26mgwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-text-search" /></template>
