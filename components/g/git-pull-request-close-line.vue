<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp7_1q3hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp7_1q3hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-pull-request-close-line" /></template>
