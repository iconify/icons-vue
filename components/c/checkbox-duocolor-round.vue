<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcu4ov-2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcu4ov-2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:checkbox-duocolor-round" /></template>
