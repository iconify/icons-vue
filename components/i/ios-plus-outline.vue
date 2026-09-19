<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxamrnbvx.css';
import '../../css/t/tiebub9tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bxamrnbvx"/><path class="tiebub9tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-plus-outline" /></template>
