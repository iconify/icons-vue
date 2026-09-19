<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f10s-hb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f10s-hb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:braces-asterisk" /></template>
