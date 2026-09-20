<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg8ox3wza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yg8ox3wza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:bookmark" /></template>
