<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqtohqphg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqtohqphg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:code-block-tag" /></template>
