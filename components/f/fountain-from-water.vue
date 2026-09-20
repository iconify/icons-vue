<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzcbppb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hzcbppb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fountain-from-water" /></template>
