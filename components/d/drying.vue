<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6b903bev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6b903bev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ginetex:drying" /></template>
