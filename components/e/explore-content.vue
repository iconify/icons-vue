<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5ct87x1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w5ct87x1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:explore-content" /></template>
