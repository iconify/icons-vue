<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhd9pdbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zhd9pdbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:health-care-2" /></template>
