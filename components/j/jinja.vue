<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fouduebcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fouduebcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:jinja" /></template>
