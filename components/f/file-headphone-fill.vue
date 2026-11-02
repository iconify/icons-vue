<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wod75ccvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wod75ccvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-headphone-fill" /></template>
