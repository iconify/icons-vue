<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzgbqj-sb.css';
import '../../css/f/fkpqvet-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hzgbqj-sb"/><path class="fkpqvet-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-briefcase" /></template>
