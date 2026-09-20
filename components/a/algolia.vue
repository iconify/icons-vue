<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuy1robfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wuy1robfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:algolia" /></template>
