<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajs7jibwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ajs7jibwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:caret-right" /></template>
