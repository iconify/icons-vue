<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lidnvnbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lidnvnbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:guitar-line" /></template>
