<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsgsakbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hsgsakbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:home" /></template>
