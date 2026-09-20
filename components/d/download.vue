<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzs-uhjos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hzs-uhjos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:download" /></template>
