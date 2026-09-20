<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v__df4xbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v__df4xbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:git" /></template>
