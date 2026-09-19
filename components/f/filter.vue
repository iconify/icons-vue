<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtj4og6cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dtj4og6cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:filter" /></template>
