<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auuyt2boe.css';
import '../../css/n/nfapznoxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="auuyt2boe"/><path class="nfapznoxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:camera-48" /></template>
