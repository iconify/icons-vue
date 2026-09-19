<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d86d3il-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="d86d3il-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:file-video" /></template>
