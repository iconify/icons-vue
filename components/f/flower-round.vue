<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmk-13lct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmk-13lct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flower-round" /></template>
