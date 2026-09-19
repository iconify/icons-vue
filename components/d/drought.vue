<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-rkgx1cc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h-rkgx1cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:drought" /></template>
