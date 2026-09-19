<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-w5amwnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l-w5amwnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:leetcode" /></template>
