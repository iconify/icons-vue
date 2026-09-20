<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dig0yubbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dig0yubbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:location-16" /></template>
