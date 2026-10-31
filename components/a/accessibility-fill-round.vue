<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuxp37epe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuxp37epe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:accessibility-fill-round" /></template>
