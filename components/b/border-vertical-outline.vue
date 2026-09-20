<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qeo4x-vgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qeo4x-vgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:border-vertical-outline" /></template>
