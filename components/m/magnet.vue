<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrlfh1-kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrlfh1-kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:magnet" /></template>
