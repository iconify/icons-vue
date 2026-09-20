<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5xyj_yyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5xyj_yyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cube-3d-sphere-off" /></template>
