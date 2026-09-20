<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz34tx__k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zz34tx__k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:angular" /></template>
