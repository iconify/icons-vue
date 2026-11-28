<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrem8qvbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrem8qvbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevrons-up-down-solid" /></template>
