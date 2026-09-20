<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm3qzydqs.css';
import '../../css/y/yb0_9vbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm3qzydqs"/><path class="yb0_9vbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dotenv" /></template>
