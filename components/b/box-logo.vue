<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fryw55bul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fryw55bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:box-logo" /></template>
