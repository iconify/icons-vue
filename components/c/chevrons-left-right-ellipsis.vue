<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbaotfb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbaotfb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chevrons-left-right-ellipsis" /></template>
