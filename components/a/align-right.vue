<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt7x1qbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mt7x1qbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:align-right" /></template>
