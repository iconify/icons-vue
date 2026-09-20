<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1ptg-o8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i1ptg-o8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:id-badge" /></template>
