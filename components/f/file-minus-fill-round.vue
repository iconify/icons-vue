<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eedpgh6qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eedpgh6qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-minus-fill-round" /></template>
