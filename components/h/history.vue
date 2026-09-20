<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqd8dx1br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yqd8dx1br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:history" /></template>
