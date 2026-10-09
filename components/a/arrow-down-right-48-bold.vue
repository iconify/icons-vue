<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glxb9obxa.css';
import '../../css/y/yq7ps8ebr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="glxb9obxa"/><path class="yq7ps8ebr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-down-right-48-bold" /></template>
