<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d976pzb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="d976pzb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:grid-small" /></template>
