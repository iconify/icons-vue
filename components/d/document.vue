<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwfr91b_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jwfr91b_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:document" /></template>
