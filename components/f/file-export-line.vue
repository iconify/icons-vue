<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l75qys3gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l75qys3gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-export-line" /></template>
