<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtq2i98hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wtq2i98hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:goto-today" /></template>
