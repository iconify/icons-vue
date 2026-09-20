<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brkjpj1te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brkjpj1te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-corner-down-left" /></template>
