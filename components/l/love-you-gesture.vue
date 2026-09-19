<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2oxn1iue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w2oxn1iue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:love-you-gesture" /></template>
