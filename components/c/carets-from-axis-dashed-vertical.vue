<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km5wu5wyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km5wu5wyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:carets-from-axis-dashed-vertical" /></template>
