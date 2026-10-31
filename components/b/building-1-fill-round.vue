<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqn6o2rec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqn6o2rec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-1-fill-round" /></template>
