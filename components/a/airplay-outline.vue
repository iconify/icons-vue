<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrvn70_6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mrvn70_6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:airplay-outline" /></template>
