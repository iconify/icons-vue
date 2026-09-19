<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k032ysbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="k032ysbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:flagalt" /></template>
