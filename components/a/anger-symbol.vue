<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us0c0obwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="us0c0obwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:anger-symbol" /></template>
