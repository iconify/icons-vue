<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv8-ysf4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tv8-ysf4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:caret-down" /></template>
