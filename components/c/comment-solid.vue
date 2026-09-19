<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qozfh9b0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qozfh9b0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:comment-solid" /></template>
