<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k46itubig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k46itubig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:angle-double-down" /></template>
