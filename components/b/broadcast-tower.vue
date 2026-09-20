<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpmv17cfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zpmv17cfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:broadcast-tower" /></template>
