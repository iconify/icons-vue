<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua-9c7bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ua-9c7bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:area-graph" /></template>
