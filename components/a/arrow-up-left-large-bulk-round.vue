<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7b8kgbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7b8kgbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-left-large-bulk-round" /></template>
