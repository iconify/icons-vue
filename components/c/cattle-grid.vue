<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qamb87bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qamb87bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cattle-grid" /></template>
