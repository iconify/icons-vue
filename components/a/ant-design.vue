<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvv5p-omy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvv5p-omy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ant-design" /></template>
