<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw_1dxbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jw_1dxbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fold-vertical-line" /></template>
