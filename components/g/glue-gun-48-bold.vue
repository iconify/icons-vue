<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmedpvb3p.css';
import '../../css/j/je85er4yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kmedpvb3p"/><path class="je85er4yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:glue-gun-48-bold" /></template>
