<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc7quy63x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fc7quy63x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:font-awesome" /></template>
