<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2srq2srb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n2srq2srb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:clutch-bag" /></template>
