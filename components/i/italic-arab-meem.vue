<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1b2s3b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p1b2s3b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:italic-arab-meem" /></template>
