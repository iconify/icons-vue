<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkvaaub1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zkvaaub1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:email-envelope-close" /></template>
