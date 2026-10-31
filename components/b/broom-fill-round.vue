<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-o94abqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-o94abqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:broom-fill-round" /></template>
