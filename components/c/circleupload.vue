<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq2os2btq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gq2os2btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circleupload" /></template>
