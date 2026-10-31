<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xglmwjqrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xglmwjqrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chess-fill-round" /></template>
