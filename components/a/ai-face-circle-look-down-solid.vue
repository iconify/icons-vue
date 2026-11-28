<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljudbibqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljudbibqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-face-circle-look-down-solid" /></template>
