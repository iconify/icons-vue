<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyi909uom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyi909uom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-4-line" /></template>
