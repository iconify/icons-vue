<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz3c6b5lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz3c6b5lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-off-fill-round" /></template>
