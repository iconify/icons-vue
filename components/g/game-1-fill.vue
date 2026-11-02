<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-a7t_fjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-a7t_fjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:game-1-fill" /></template>
