<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc0hhlbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1280,"height":1536};
const content = `<path class="qc0hhlbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:bookmark-o" /></template>
