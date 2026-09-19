<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn6ebachz.css';
import '../../css/z/zeqvi16vh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vn6ebachz"/><path class="zeqvi16vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-angular" /></template>
