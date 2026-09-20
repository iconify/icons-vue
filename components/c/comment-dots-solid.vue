<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoxv6tbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zoxv6tbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:comment-dots-solid" /></template>
