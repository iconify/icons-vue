<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_5wbj6qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_5wbj6qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:bookmark-thin" /></template>
