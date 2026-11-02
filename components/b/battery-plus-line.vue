<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty6or5guf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty6or5guf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-plus-line" /></template>
