<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_92r26un.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c_92r26un"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:dress" /></template>
