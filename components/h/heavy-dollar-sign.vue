<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm_agbbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fm_agbbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:heavy-dollar-sign" /></template>
