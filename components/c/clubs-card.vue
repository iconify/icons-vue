<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy8n1abgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="wy8n1abgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:clubs-card" /></template>
