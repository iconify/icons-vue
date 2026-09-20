<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5r9tz_qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5r9tz_qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-alt-lock" /></template>
