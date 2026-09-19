<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tieasjbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tieasjbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-watermark" /></template>
