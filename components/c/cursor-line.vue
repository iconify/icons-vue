<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gly0l3bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gly0l3bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cursor-line" /></template>
