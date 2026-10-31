<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjfi-ebyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjfi-ebyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bird-fill-round" /></template>
