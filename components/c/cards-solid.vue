<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhxk1hsjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zhxk1hsjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cards-solid" /></template>
