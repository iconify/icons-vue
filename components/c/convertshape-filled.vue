<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa31wen-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa31wen-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:convertshape-filled" /></template>
