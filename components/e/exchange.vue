<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1a2rhbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w1a2rhbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:exchange" /></template>
