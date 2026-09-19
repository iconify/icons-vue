<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzbzo6yfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tzbzo6yfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:border-style" /></template>
