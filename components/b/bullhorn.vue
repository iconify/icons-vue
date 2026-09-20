<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpgjlybvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fpgjlybvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bullhorn" /></template>
