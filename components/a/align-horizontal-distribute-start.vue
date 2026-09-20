<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbuufs0zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbuufs0zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-horizontal-distribute-start" /></template>
