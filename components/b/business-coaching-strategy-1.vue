<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7u6b6bui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d7u6b6bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:business-coaching-strategy-1" /></template>
