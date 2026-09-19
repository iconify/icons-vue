<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf1zk3yha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf1zk3yha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:fire-hose" /></template>
