<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja4g38bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ja4g38bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:activeloop" /></template>
