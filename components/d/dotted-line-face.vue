<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_yphdctb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n_yphdctb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:dotted-line-face" /></template>
