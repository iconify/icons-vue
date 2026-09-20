<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq3ziibii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="tq3ziibii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:direction-down-left" /></template>
