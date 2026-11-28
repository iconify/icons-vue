<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys7dy7tqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys7dy7tqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:key-plus" /></template>
