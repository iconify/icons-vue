<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1c6xhbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1c6xhbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-to-left-line" /></template>
