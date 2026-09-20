<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myp90-ogc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="myp90-ogc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hotdog" /></template>
