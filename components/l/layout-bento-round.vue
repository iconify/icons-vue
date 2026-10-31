<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdq7d7bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdq7d7bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:layout-bento-round" /></template>
