<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsks7abtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsks7abtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:angry-line" /></template>
