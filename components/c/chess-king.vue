<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y96dk-70z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="y96dk-70z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chess-king" /></template>
