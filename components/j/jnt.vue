<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbsj5lbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bbsj5lbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:jnt" /></template>
