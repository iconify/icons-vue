<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6x76mbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6x76mbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eraser-round" /></template>
