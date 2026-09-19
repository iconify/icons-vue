<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdrcr1l6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cdrcr1l6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:join-node" /></template>
