<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2m5ehb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t2m5ehb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:array-users" /></template>
