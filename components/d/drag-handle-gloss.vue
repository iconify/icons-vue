<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h06fjmfvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h06fjmfvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:drag-handle-gloss" /></template>
