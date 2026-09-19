<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp8e4qb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zp8e4qb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:beam" /></template>
