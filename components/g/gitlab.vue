<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9-3slunj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a9-3slunj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:gitlab" /></template>
