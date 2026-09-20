<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhlffspxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhlffspxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:contacts-3-line" /></template>
