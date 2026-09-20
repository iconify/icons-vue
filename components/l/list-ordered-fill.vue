<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtn8ih8gz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtn8ih8gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-ordered-fill" /></template>
