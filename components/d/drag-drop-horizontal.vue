<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vflv5-bqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vflv5-bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:drag-drop-horizontal" /></template>
