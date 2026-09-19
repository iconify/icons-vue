<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wum6unbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wum6unbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:behance-square" /></template>
