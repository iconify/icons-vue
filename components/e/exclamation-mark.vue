<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypa0l_ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ypa0l_ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:exclamation-mark" /></template>
