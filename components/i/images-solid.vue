<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqpzy1b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yqpzy1b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:images-solid" /></template>
