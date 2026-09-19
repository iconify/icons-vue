<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gae3ks5tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gae3ks5tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:black-large-square" /></template>
