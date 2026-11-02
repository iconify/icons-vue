<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4-prbbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4-prbbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grid-2x2-plus-line" /></template>
