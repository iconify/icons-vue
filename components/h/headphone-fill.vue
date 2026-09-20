<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jggrwgbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jggrwgbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:headphone-fill" /></template>
