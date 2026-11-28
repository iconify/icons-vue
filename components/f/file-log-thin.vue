<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rylf6pbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rylf6pbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-log-thin" /></template>
