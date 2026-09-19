<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wewar8boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wewar8boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:job-daemon" /></template>
