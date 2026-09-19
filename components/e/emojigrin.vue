<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfo7s3bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qfo7s3bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:emojigrin" /></template>
