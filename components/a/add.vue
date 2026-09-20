<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5zn8ca3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q5zn8ca3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:add" /></template>
