<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do0-t4b8n.css';
import '../../css/q/qf6fzcbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do0-t4b8n"/><path class="qf6fzcbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:book-content" /></template>
