<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyshgbbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyshgbbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-minus-corner-fill" /></template>
