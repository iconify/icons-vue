<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0rokl91k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m0rokl91k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:info" /></template>
