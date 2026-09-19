<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjzmy7b4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="yjzmy7b4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:confluence" /></template>
