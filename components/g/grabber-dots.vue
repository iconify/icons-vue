<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu2a-wbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hu2a-wbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:grabber-dots" /></template>
