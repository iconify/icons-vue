<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn58tbcdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bn58tbcdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:check" /></template>
