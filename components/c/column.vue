<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5okodbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j5okodbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:column" /></template>
