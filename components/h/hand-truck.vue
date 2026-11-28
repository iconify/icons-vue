<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsjpldb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zsjpldb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:hand-truck" /></template>
