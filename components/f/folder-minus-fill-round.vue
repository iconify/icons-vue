<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyj9v4bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyj9v4bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-minus-fill-round" /></template>
