<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3q631rcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3q631rcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bed-round" /></template>
