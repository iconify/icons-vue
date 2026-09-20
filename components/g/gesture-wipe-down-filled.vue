<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru6zld64q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru6zld64q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:gesture-wipe-down-filled" /></template>
