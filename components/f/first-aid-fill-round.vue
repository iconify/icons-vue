<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc6opcb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc6opcb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:first-aid-fill-round" /></template>
