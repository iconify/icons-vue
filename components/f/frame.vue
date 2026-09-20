<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru7if7xhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru7if7xhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:frame" /></template>
