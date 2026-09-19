<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxbqhgb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="attachment-clip-outline"><path class="Vector wxbqhgb_a" clip-rule="evenodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:attachment-clip-outline" /></template>
