<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxcwr8xud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxcwr8xud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-top-right-bold-box" /></template>
