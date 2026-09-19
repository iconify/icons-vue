<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uan6h8bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uan6h8bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:branch-fork" /></template>
