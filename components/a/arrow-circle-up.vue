<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xts5eub8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xts5eub8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-circle-up" /></template>
