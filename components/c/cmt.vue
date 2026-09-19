<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouhonqmbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ouhonqmbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:cmt" /></template>
