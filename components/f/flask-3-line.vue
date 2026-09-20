<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7e7pvb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7e7pvb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flask-3-line" /></template>
