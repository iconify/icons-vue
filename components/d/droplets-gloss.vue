<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w61v8s2md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w61v8s2md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:droplets-gloss" /></template>
