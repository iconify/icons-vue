<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydd2y3hhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ydd2y3hhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:crane" /></template>
