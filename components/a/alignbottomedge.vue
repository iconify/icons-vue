<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1pkisb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="u1pkisb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:alignbottomedge" /></template>
