<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2r3y2b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2r3y2b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hands-clapping-line" /></template>
