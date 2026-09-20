<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yolcwwbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yolcwwbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-remove-multiple-outline" /></template>
