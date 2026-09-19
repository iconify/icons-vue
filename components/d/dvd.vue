<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za7uqbcjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="za7uqbcjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:dvd" /></template>
