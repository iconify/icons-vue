<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni7dbrlty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni7dbrlty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:grid" /></template>
