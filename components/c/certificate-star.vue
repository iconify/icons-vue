<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt82v1dak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt82v1dak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:certificate-star" /></template>
