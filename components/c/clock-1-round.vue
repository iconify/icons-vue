<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3t8qpbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3t8qpbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-1-round" /></template>
