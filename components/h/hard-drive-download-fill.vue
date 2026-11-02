<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys3s1y12f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys3s1y12f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hard-drive-download-fill" /></template>
