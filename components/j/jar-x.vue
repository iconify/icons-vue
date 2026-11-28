<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh7ko11ac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh7ko11ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:jar-x" /></template>
