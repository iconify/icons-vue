<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f62sy9bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="f62sy9bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:filter-highpass" /></template>
