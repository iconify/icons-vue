<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oquv4muql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oquv4muql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ip" /></template>
