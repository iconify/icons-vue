<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9g7eebku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9g7eebku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-arrow-right-round" /></template>
