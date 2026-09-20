<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxxjubt8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxxjubt8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-turn-forward-line" /></template>
