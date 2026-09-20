<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j21tacc4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j21tacc4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:digg" /></template>
