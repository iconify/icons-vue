<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yue8hubqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yue8hubqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-off-round" /></template>
