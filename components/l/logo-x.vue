<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsuq6xb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zsuq6xb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-x" /></template>
