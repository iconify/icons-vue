<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqm3efwxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wqm3efwxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:btt" /></template>
