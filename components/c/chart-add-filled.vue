<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9penwvtt.css';
import '../../css/f/f-2vaaboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9penwvtt"/><path class="f-2vaaboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chart-add-filled" /></template>
