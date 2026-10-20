<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9bgxeb0o.css';
import '../../css/c/ccjw-8b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y9bgxeb0o"/><path class="ccjw-8b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:line-height-20-bold" /></template>
