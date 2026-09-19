<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7-w7-baa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="c7-w7-baa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:double-chevron-down-12" /></template>
