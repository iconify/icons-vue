<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytsullcxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ytsullcxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:large-blue-diamond" /></template>
