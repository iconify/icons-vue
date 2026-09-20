<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrhgz1lsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrhgz1lsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:cancel" /></template>
