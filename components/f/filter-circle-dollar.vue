<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwan7fbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qwan7fbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:filter-circle-dollar" /></template>
