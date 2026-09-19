<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th45_7bih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th45_7bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:file-archive" /></template>
