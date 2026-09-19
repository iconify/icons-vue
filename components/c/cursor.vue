<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/damdljbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":340,"height":651};
const content = `<path class="damdljbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:cursor" /></template>
