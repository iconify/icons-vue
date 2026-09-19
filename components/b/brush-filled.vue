<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzqhaxd9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lzqhaxd9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:brush-filled" /></template>
