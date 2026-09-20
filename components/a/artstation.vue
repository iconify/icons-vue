<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv3zubhup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yv3zubhup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:artstation" /></template>
