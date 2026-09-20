<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4d9v6lqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f4d9v6lqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:badge-shield-with-deer-head-with-antlers" /></template>
