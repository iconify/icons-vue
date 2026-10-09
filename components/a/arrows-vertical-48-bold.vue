<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arf8ercmz.css';
import '../../css/w/wmf5h3zqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="arf8ercmz"/><path class="wmf5h3zqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrows-vertical-48-bold" /></template>
