<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d180j-q7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="d180j-q7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:file-video" /></template>
