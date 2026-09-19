<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd07mlbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd07mlbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:like" /></template>
