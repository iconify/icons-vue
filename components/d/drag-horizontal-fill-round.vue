<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl8o6hhxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl8o6hhxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:drag-horizontal-fill-round" /></template>
