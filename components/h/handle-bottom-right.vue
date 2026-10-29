<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhi6qobkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhi6qobkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:handle-bottom-right" /></template>
