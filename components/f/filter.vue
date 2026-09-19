<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2u1amfii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y2u1amfii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:filter" /></template>
