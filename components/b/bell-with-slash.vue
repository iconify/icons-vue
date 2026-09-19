<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5r145l-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h5r145l-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:bell-with-slash" /></template>
