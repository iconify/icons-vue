<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws-o9bc6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ws-o9bc6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:lightbulb-fill-12" /></template>
