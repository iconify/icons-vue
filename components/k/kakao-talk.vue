<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg2ssfjpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="xg2ssfjpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:kakao-talk" /></template>
