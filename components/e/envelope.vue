<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg4x4-miu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg4x4-miu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:envelope" /></template>
