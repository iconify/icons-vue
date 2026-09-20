<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si2ppcpkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="si2ppcpkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-text-formatting-paragraph-article-alignment-formatting-normal-paragraph-text" /></template>
