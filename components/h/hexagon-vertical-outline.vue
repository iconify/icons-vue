<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq6pc5b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zq6pc5b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:hexagon-vertical-outline" /></template>
