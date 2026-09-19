<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3y1o4bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f3y1o4bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:awareness-ribbon" /></template>
