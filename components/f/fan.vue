<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqj42rb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yqj42rb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:fan" /></template>
