<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2kgjwa6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2kgjwa6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-chevron-right-round" /></template>
