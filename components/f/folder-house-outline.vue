<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvtq6ac7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvtq6ac7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-house-outline" /></template>
