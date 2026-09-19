<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5u55absk.css';
import '../../css/q/qvuh0pbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s5u55absk"/><path class="qvuh0pbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-straight-filled" /></template>
