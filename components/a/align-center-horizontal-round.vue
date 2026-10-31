<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyt6-xbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyt6-xbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-center-horizontal-round" /></template>
