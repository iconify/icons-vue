<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbqzj5bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<g transform="translate(1536 0) scale(-1 1)"><path class="wbqzj5bhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:chevron-circle-right" /></template>
