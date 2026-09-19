<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y82gy9b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="y82gy9b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:hornbill" /></template>
