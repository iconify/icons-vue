<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf5znccoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf5znccoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:edit" /></template>
