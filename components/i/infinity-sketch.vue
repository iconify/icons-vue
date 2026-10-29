<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhp12cbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhp12cbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:infinity-sketch" /></template>
