<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/namhj9b3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="namhj9b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bar-chart-stroke-20" /></template>
