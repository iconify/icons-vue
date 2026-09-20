<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc3d2blkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc3d2blkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:box-3-line" /></template>
