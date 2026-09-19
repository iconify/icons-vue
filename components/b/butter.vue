<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hml-ltb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hml-ltb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:butter" /></template>
