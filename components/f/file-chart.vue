<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjuimz9ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjuimz9ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-chart" /></template>
