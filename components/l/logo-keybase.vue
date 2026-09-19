<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydf994boj.css';
import '../../css/e/ev5zxibtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ydf994boj"/><path class="ev5zxibtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-keybase" /></template>
