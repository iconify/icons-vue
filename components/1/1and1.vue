<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-5-hx-wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-5-hx-wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:1and1" /></template>
