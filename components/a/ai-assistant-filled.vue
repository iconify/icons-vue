<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baxcrzb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="baxcrzb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:ai-assistant-filled" /></template>
