<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/todpwgbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="todpwgbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:letters-w" /></template>
