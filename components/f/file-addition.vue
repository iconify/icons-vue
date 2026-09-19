<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8-v5vbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h8-v5vbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:file-addition" /></template>
