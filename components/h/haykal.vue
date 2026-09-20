<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8sr93jgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p8sr93jgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:haykal" /></template>
