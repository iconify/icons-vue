<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi01502br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wi01502br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:beauty-cosmatic-brush-set" /></template>
