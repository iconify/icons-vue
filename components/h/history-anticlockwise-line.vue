<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj4txcc8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj4txcc8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:history-anticlockwise-line" /></template>
