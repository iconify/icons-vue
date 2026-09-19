<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2blh9boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="c2blh9boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:layers" /></template>
