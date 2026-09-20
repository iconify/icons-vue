<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q378etc0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q378etc0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:graduation-cap" /></template>
