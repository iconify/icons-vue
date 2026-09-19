<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re9d79bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="re9d79bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:crow" /></template>
