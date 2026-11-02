<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrre46b4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrre46b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-chevrons-up-down-fill" /></template>
