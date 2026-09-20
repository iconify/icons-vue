<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww36-hbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ww36-hbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:door-solid" /></template>
