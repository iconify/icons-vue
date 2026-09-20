<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqsq_tbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqsq_tbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:brackets" /></template>
