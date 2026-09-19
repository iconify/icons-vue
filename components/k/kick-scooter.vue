<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz4dt-pak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zz4dt-pak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:kick-scooter" /></template>
