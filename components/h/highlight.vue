<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yri5-ac-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yri5-ac-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:highlight" /></template>
