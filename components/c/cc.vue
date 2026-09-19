<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh-fjtb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bh-fjtb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:cc" /></template>
