<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4x-kekqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="f4x-kekqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:caret-bottom-left-solid-8" /></template>
