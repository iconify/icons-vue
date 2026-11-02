<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynvx9g5yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynvx9g5yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:figma-fill" /></template>
