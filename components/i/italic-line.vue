<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osedu1b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osedu1b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:italic-line" /></template>
