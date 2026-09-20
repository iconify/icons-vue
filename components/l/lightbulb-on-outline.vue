<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lusdtq8gq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lusdtq8gq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-on-outline" /></template>
