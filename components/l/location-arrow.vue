<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpn0pzs8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fpn0pzs8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:location-arrow" /></template>
