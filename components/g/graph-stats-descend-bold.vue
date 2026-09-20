<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn279sbtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn279sbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:graph-stats-descend-bold" /></template>
