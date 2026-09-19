<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2sj9mb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="w2sj9mb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:eject" /></template>
