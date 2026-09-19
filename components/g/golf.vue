<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl4o3acey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yl4o3acey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:golf" /></template>
