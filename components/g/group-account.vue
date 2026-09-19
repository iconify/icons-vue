<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doyhfwb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="doyhfwb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:group-account" /></template>
