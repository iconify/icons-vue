<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-yksqnjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n-yksqnjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:file-tray-stacked" /></template>
