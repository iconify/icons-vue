<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys01xebuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ys01xebuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:double-quote-sans-left" /></template>
