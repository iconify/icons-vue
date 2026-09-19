<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d53h_wb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="d53h_wb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:lock-share" /></template>
